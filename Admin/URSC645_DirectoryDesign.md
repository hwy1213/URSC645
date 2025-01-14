## Directory and Folder Name Structure

**Admin**      = Administration Folder = Folder has files and guides to introduce project. Folder may contain proposals, budgets, hiring documents, etc.

**SourceData** = Folder contains data that many project members may want to use. 
The goal is to not have multiple copies of the same files. 
Also to preserve the original data and metadata.

**Projects** = [_Optional_] Folder contains subprojects for the main project - usually specific to an individual person or team.

**Tasks** = [_Optional_] Folder contains tasks - usually a specific activity that anyone on project may need to accomplish. For example, setting up the python environment or completing a specific training. Tasks are related to the main project or could be within a subproject.

**Work[]** = Work folders will be found inside a project or task folder. Work folder names include the initials of the person. For example, Nathanael's work folders are named WorkNPR (work folder for Nathanael P. Rosenheim). Work folders contain any files, documents, generated data... related to the specific project or task. Work folders should also include a WorkLog file specific to the project or task. 

**Posted** = Archived files needed for replicating work that has been shared - 
- journal article
- conference paper
- poster
- data archive
- work shared internally for the team
In replication scripts DO NOT SAVE to or READ from the Posted folder. The Posted folder is for archiving only. You should only copy from your Work folder to paste into the Posted folder or copy files from the Posted folder to be pasted in your Work folder.
        
**Readings** = [_Optional_] Folder contains readings related to the project.

***Note on directory names*** Directory names should not contain spaces. Use Camel Case and/or underscores "_" to separate words.

**Archive** = [_Optional_] As a folder gets cluttered it is good to clean up with an archive folder. The folder can contain old versions of scripts or out-of-date files that are not needed for replication. Archive folders are a great way to clean up a Work Folder or the Posted Folder. It is good to keep old versions of files in case you need to go back to them.

## USE RELATIVE PATHS 
The directory design is intended to be used with relative paths.
For more information on how to use relative paths see: https://www.kaggle.com/code/rtatman/reproducibility-tips-absolute-vs-relative-paths

If you apply this directory design a file that is Posted from one Work Folder will run in another Work Folder. 