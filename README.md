<html>
<head>
<script>
var temp="";
var GBP = function (elm) {
	if(!isNaN(Number(elm.target.value))){
	//only for number
		//temp=elm.target.value;
		if(elm.target.value.indexOf(".")!="-1") {		
			if(elm.target.value.indexOf(".")<=10){
			if(elm.target.value.split(".")[1].length>2){
			elm.target.value=elm.target.value.slice(0,elm.target.value.length-1); 
			}
			}else if(elm.target.value.split(".")[0].length>10){
			
			temp2 = elm.target.value.split(".")[1];
			temp1 = elm.target.value.slice(0,elm.target.value.split(".")[0].length-1);
			elm.target.value=temp1 + "."+temp2; 
			}
			
		
		}else{
				if((elm.target.value.length)>10){
						elm.target.value=elm.target.value.slice(0,elm.target.value.length-1); 
				}
			}
		
	}
	else {
		elm.target.value=temp; //only for char
	}
	
	
}
</script>
</head>
<body>
<input type="text" onkeyup="GBP(event)" oninput="this.value.replace(/[^0-9\.]/g,'')">
</body>
</html>
