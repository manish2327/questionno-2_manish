# questionno-2_manish
Question no-2 

<?php 
function Countt($str) 
{ 

    $upper = 0;  

    $lower = 0; 

    $number = 0; 

    $special = 0; 

    for ($i = 0; $i < strlen($str); $i++) 

    { 

        if ($str[$i] >= 'A' &&  

            $str[$i] <= 'Z') 

            $upper++; 

        else if ($str[$i] >= 'a' &&  

                 $str[$i] <= 'z') 

            $lower++; 

        else if ($str[$i]>= '0' &&  

                 $str[$i]<= '9') 

            $number++; 

        else

            $special++; 

    } 

    echo "Upper case letters: " , $upper,"\n" ; 

    echo "Lower case letters : " ,$lower,"\n" ; 

    echo "Number : " , $number ,"\n"; 

    echo ucwords($str_first_cap);     

echo ucfirst($str_cap_one);
} 
   

 $str = "EduCatiON"; 

    Countt($str); 
?>
