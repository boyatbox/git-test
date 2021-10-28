## Show whats in the index
    git ls-files --stage

## Remove a file from index
    git rm --cached index.html

## Remove file from index and the working directory
    git rm index.html

## Track full history of a file after it is renamed
    git log --follow index.html