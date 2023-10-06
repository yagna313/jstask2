# jstask2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>

 //task-1 
         var a=+prompt("enter time")
         if (a<=11){
           console.log("morning");
         }else if (a>=11 && a<=17){
            console.log("afternoon");
         }else if (a>=17 && a<=21){
         console.log("evening");
         }else if(a>=21 && a<=24){
            console.log(" night");
         }
         else{
         console.log("in valid");
         }

        //task-2 )

         var a=+prompt("enter a")
         var b=+prompt("enter b")
         var c=+prompt("enter c")
         if (a>b && a>c){
            alert("a is greater")
         }
         else if(b>a && b>c){
            alert("b is greater")
         }
          else{
            alert("c is greater ")
         }

        //task-3 
         var a=+prompt("enter a")
         var b=+prompt("enter b")
         if (a>b){
         alert("a is greater")
         }
         else{
         alert("in valid")
         }
       //task-4 

         var z=+prompt("enter a day")
         if (z==0){
         alert("sunday")
         }
         else if (z==1){
         alert("monday")
         }
         else if(z==2){
        alert("tuesday")
         }
         else if(z==3){
            alert("wednesday")
         }
         else if(z==4){
        alert("thursday")
         }
         else if(z==5){
            alert("friday")
         }
         else if(z==6){
            alert("saturday")
         }
         else{
         alert("in valid")
         }
           //task-5 
         var month=+prompt("enter a month")
         switch(month){
            case 1:
            alert("januaray");
            break;
         case 2:
            alert("febuary");
         break;
            case 3:
            alert("march");
            break;
            case 4:
            alert("april");
            break;
            case 5:
            alert("may");
            break;
            case 6:
            alert("june");
            break;
            case 7:
            alert("july");
            break;
            case 8:
            alert("august");
            break;
            case 9:
            alert("september");
            break;
            case 10:
            alert("october");
            break;
            case 11:
            alert("november");
            break;
            case 12:
            alert("december");
           break;
            default:
           alert("in valid")
         }
       //task-6 
         var a=+prompt("enter a")
         var b=+prompt("enter b")
         var c=prompt("enter c")
         if (c=="+"){
         alert(a+b)
         }
         else if(c=="-"){
         alert(a-b)
         }
         else if (c=="/")
         {
         alert(a/b)
         }
        else if(c=="*")
         {
            alert(a*b)
         }
         else if(c=="%")
        {
        alert(a%b)  
         }
         else
         {
            alert("in valid oparator")
         }


        //task-7 
         var a=prompt("enter a")
         if (a%2==0){
           alert("even")
         } 
         else{
           alert("odd")
         }

        //task-8
         var a=+prompt("enter  num")
         if (a%1==1) {
            alert("prime num")
         }
         else{
         alert("in valid prime")
         }

    </script>
</body>
</html>



</script>

</body>
</html
