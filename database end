<?php
$con=mysqli_connect('localhost','root','','passworddirectory');
if($con)
{
    echo "Connection created";
} 
else
{
    echo "Connection failed";
}    
if(isset($_POST['sb']))
{
    $platform=$_POST['pf'];
    $regemail=$_POST['em'];
    $regmobno=$_POST['mob'];
    $rdate=$_POST['dp'];
    $pswrd=$_POST['pas'];
    $username=$_POST['user'];
    
    $query="INSERT INTO DETAILS VALUES('$platform','$regemail','$regmobno','$rdate','$pswrd','$username')";
    $data=mysqli_query($con,$query);
    if($data)
    {
        echo "Data is inserted";
    }
    else 
    {
        echo "failed";
    }   
}


?>
