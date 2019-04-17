# Zip each folder in directory
for i in */; do zip -r "${i%/}.zip" "$i"; done
