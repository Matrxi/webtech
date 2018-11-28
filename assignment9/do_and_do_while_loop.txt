<!DOCTYPE html>
<html>
<head>
<title>Do and do while loop in PHP</title>    
</head>    

<body>
    <h2>Using while loop to print table of 2</h2>
    <?php 
        $num=2;
        $i=1;
        while($i<=  10){
            $temp=($num*$i);
            echo "$num * $i = $temp <br/>";
            $i++;
        }
        
    ?>  

    <h2>Using do-while loop to print table of 5</h2>
    <?php
        $num=5;
        $i=1;
        do
        {
            $temp=($num*$i);
            echo "$num * $i = $temp </br>";
            $i++;
        }while($i<=10);
    ?>
</body>
    
</html>
