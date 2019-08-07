CreateVersionINI.exe - utility to read .Ver file and convert to .ini for SetupBuilder
INPUT=<Path to .VerFile>
OUTPUT=<Path to .INI File>
VersionVar=<Equate name with Production Version>
VersionVarRes=<Equate name with Production Version or resource>

Example .Ver
DLLTutor_VERSION     		EQUATE('ClarionLive Dll Tutor 2017')
DLLTutor_VERSION_NUMBER    	EQUATE('2017 B')
DLLTutor_VERSION_YEAR      	EQUATE('2017')
DLLTutor_VERSION_BUILD     	EQUATE('B.1')
DLLTutor_VERSION_DB        	EQUATE('2017_B')
DLLTutor_VERSION_INHOUSE_DB EQUATE('0004')
VERSION_RESOURCE_VER        EQUATE('2017,2,1')
VERSION_VALUE_RESOURCE_VER  EQUATE('2017.2.1')

UP_FileVersion.tpl - Enhanced version of Softvelocity template to create file version resource from .Ver file


UP_BrowseHelper.tpw - example template to generate equates for each column in a ABC browse list control. 
			These equates can be used instead of hard coded numeric constants in code where you need the column number.
			The equate automatically generates the correct value if the order of the columns change or new columns are added.