
<?php

session_start();



?>
<?php



//unset($_SESSION);
//unset($_SESSION["records"]);
//$_SESSION["records"] = "";

if (isset($_SESSION["records"])) {
    $records = $_SESSION["records"];
} else {
    $records = array();
}

if (filter_has_var(INPUT_GET, "add")) {
    $item = array();

    $item[] = uniqid().time();
    $item[] = filter_input(INPUT_GET, "name");
    $item[] = filter_input(INPUT_GET, "surname");
    $item[] = filter_input(INPUT_GET, "gender");
    $item[] = filter_input(INPUT_GET, "address");
    $item[] = filter_input(INPUT_GET, "age");
    $item[] = filter_input(INPUT_GET, "email");
    
     $item[] = filter_input(INPUT_GET, "status");
    //$item[] = filter_input(INPUT_GET, "description");
    

    $records[] = $item;
    $_SESSION["records"] = $records;
} else if (filter_has_var(INPUT_GET, "delete")) {
    $id = filter_input(INPUT_GET, "delete-id");

    for ($i = 0; $i < count($records); $i++) {
        if ($records[$i][0] == $id) {
            unset($records[$i]);
            $records = array_values($records);
            $_SESSION["records"] = $records;
            break;
        }
    }
} else if (filter_has_var(INPUT_GET, "edit")) {
    $id = filter_input(INPUT_GET, "edit-id");

    for ($i = 0; $i < count($records); $i++) {
        if ($records[$i][0] == $id) {
            $records[$i][1] = filter_input(INPUT_GET, "name");
            $records[$i][2] = filter_input(INPUT_GET, "surname");
            $records[$i][3] = filter_input(INPUT_GET, "gender");
            $records[$i][4] = filter_input(INPUT_GET, "address");
            $records[$i][5] = filter_input(INPUT_GET, "age");
            $records[$i][6] = filter_input(INPUT_GET, "email");
            $records[$i][7] =  filter_input(INPUT_GET, "status");
         // $records[$i][7] =  filter_input(INPUT_GET, "status2");
            
            $_SESSION["records"] = $records;
            break;
        }
    }
}
?>

<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title></title>
        
        <link rel="stylesheet" href="css/bootstrap.min.css" />
    </head>
    <body>
        <?php
        //echo "UNIQID: " . uniqid() . "-" . time();
        ?>
        <a href="add.php">
            <button>Add</button>
        </a>
        <a href="details.php">
            <button>Details</button>
        </a>

        <table>
            <tr>
                
                
                
                <th>Name</th>
                <th>Surname</th>
                <th>Gender</th>
                <th>Address</th>
                <th>Age</th>
                <th>Email</th>
                <th>Employed</th>
                
            </tr>
            <?php
            foreach ($records as $item) {
                ?>
                <tr>
                    <td><?php echo $item[1]; ?></td>
                    <td><?php echo $item[2]; ?></td>
                    <td><?php echo $item[3]; ?></td>
                    <td><?php echo $item[4]; ?></td>
                    <td><?php echo $item[5]; ?></td>
                    <td><?php echo $item[6]; ?></td>
                    <td><?php echo $item[7]; ?></td>
                    <td>
                        <form action="edit.php" method="get">
                            <input type="hidden" name="edit-id" value="<?php echo $item[0]; ?>" />
                            <button type="submit" name="edit">Edit</button>
                        </form>
                    </td>
                    <td>
                        <form action="index.php" method="get">
                            <input type="hidden" name="delete-id" value="<?php echo $item[0]; ?>" />
                            <button type="submit" name="delete">Delete</button>
                        </form>
                    </td>
                </tr>
                <?php
            }
            ?>
        </table>
        
        <script src="js/bootstrap.min.js"></script>
    </body>
</html>






