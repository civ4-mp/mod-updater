The file 'Updater_DLL_CHANGES.diff' contains the changes to the 
original Civ4:BTS source code.
You can update your code base like:

cp Updater_DLL_CHANGES.diff Updater.res {YOUR CVGAMECOREDLL-DIR} 
cd {YOUR CVGAMECOREDLL-DIR} 
git checkout 'original bts code'
git checkout -b 'mod-updater'
git apply Updater_DLL_CHANGES.diff

