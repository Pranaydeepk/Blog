E:
cd E:\quartz
git pull origin v4
git add .
git commit -m "Updated Obsidian notes for sync"
git push origin v4
npx quartz sync
