# briup
实训作业

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>2.数组去重</title>
    <script>
        document.write("第二题：数组去重：");
        document.write("<br>");
        document.write("<br>");
        var arr = [1,2,3,4,5,3,4,6,8,1];
       document.write("去重前的数组：",arr);
       document.write("<br>");
       document.write("<br>");
        // var result1 = new Array;
      
        // for(var i=0;i<arr.length;i++){
        //     var result = arr.indexOf(arr[i]);
        //     if(result ==-1){
        //        result1 =arr[i];
        //     }
        // }
        // console.log(result1);


	function fun(){
		var Arr1 = [];
		for (var i = 0; i < arr.length; i++) {
			if (Arr1.indexOf(arr[i]) == -1 ) {
				Arr1.push(arr[i]);
			}
		}
		document.write("去重后的数组：",Arr1);
	}
	fun(arr);
    </script>
</head>
<body>
    
</body>
</html>
