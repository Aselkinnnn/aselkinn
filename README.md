<script>

var sum=0
var matrixExample = [
[ 1, 2, 3, 4 ],
[ 4, 5, 6, 5 ],
[ 7, 8, 9, 7 ],
[ 7, 8, 9, 7 ]
];
function sumUpDiagonals(matrix) {
for(var i=0; i<4; i++){
sum += matrix[i][i]+matrix[i][4-i-1];
}
}

console.log(sumUpDiagonals(matrixExample))
alert(sum) 
</script>
