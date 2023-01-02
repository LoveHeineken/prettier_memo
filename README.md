npm i --save-dev prettier
npm i --save-dev --save-exact prettier
npx prettier --write file_name_to_modify.js
npx prettier --check file_name_to_check.js
install prettier extention on VScode
setting → seacrh "prettier" → text editor → Default formatter → Prettier
setting → seacrh "prettier" → prettier → semi → remove check
setting → seacrh "format on save" → Formatting → check
if you want to ignore prettier rules for some files → create ".prettierignore"
if you want your own prettier rule file → create ".prettierrc"
if you have conflicts against eslint → create ".eslintrc" and install bottom
npm i --save-dev eslint-config-prettier
