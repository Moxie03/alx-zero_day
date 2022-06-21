mkdir 0x03-git in alx-zero_day repo
cd 0x03-git
echo 'second readme' > README.md
cat README.md
mkdir bash, c, js
cd c
touch c_is_fun.c
cd ..
cd js
touch main.js, index.js
cd ..
cd bash
echo '#!/bin/bash' > alx
echo 'echo "ALX"' >> alx
echo '#!/bin/bash' > school
echo 'echo "School"' >> school
cd ..
git add .
git commit -m 'commit message'
git push
