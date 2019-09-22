# 1.Name
### Aliaksandr Chachura

# 2.Contacts
### Email: skif198560@gmail.com
### Tel.: +375-29-361-30-98

# 3.Summary
### The main purpose become a good specialist in Front-end developing. I would like to take more skills in this direction. Although I haven't enaugh experience in programming, I'  m ready to study all the time to improve my skills. 
### In the beginning of 2019 year I studied in RSSchool, but unfortuantly I couldn't graduated from it, my training lasted only 1,5 stages. And now I'm trying to complete this education. 

# 4.Skills
### Good level of Java Script, can build an enviroment for application, know such tools as WebSocket, WebPack. Can work using Git. Have knowledge of HTML and CSS.

# 5.Code examples
* solve of Sudoku
```javascript
 function solveSudoku(matrix) {
        if (solve(matrix) === true)
            return matrix;
    }

    function solve(matrix) {
        let b;
        for (let i = 0; i <= 8; i++) {
            for (let j = 0; j <= 8; j++) {
                if (matrix[i][j] !== 0) {
                    continue;
                }
                for (let k = 1; k <= 9; k++) {
                    if (insert(matrix, i, j, k) === true) {
                        matrix[i][j] = k;
                        b = solve(matrix);
                        if (b === true) {
                            return true;
                        }
                        matrix[i][j] = 0;
                    }
                }
                return false;
            }
        }

        return true;

    }

    function insert(matrix, i, j, k)
    {
        for (let a = 0; a <= 8; a++) {
            if ((a !== i && matrix[a][j] === k) || (a !== j && matrix[i][a] === k)) {
                return false;
            }
        }
        let y = Math.floor((i / 3)) * 3;
        let x = Math.floor((j / 3)) * 3;
        for (let a = 0; a < 3; a++) {
            for (let b = 0; b < 3; b++) {
                if (a !== i && b !== j && matrix[y + a][x + b] === k) {
                    return false;
                }
            }
        }
        return true;


}
```
* Link to сode of site design using HTML model is made in terms of CSS framework.
[GitHub](https://github.com/AliaksandrChachura/hexal)

# 7.Education
1. Studied C in 2010 in BELHARD;
1. Studied PHP in 2010 in BELHARD;
1. Studied VBA Excel in 2017 in Courcera.

# 6.English
### Intermediate, sometimes use english in my job. Also use english to search information in internet.