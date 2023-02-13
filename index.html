<?php
    $servername="localhost";
    $username="root";
    $pasword="";
    $dbname="notes";
    $conn =mysqli_connect($servername,$username,$pasword,$dbname);
    if(!$conn)
    {
        die("Sorry we failed to connect: ".mysqli_connect_error());

    }
    if ($_SERVER["REQUEST_METHOD"] == "POST")
    {
        if($_GET['key']=='update')
      {
          
          $sn=$_POST['sn_edit'];
          $title= $_POST['title_edit'];
          $des=$_POST['note_edit'];
          $sql="UPDATE `notes` SET `Title`='$title' ,`Des`='$des' WHERE `Title`='$sn'";
          $result=mysqli_query($conn,$sql);
            
      }

    
    
    if($_GET['key']=='insert')
    {
      
      
          $title= $_POST['title'];
          $des=$_POST['note'];
          $sql="INSERT INTO `notes` (`Title`,`Des`) VALUES ('$title','$des')";
          $result=mysqli_query($conn,$sql);
          
      
    }
    if($_GET['key']=='delete')
    {
      
      
          $title= $_POST['sn_dele'];
          $sql="DELETE FROM `notes` WHERE `title`='$title'";
          $result=mysqli_query($conn,$sql);
          
      
    }

  }
    
    
  
    
    
    // mysqli_close($conn);
?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Notes</title>
</head>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous">
  <style>
        #out{
            background-color: rgba(128, 128, 128, 0.475);
            box-shadow: 0 0 5px black;
            width: 400px;
        }
        body::-webkit-scrollbar
    {
      background-color:white;
    }
   
    body::-webkit-scrollbar-thumb
    {
      background-color:rgb(7, 101, 209);
      border-radius: 20px;
    }
    </style>
    
  <link rel="stylesheet" href="//cdn.datatables.net/1.13.1/css/jquery.dataTables.min.css">
<body>

<!-- Modal -->
<div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h1 class="modal-title fs-5" id="exampleModalLabel">Edit Note</h1>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
      <form action="http://localhost/cruwd.php/cruwd.php?key=update" method="post">
                <div class="form-group">
                  <input type="text" style="display:none;" name="sn_edit" id="sn_edit">
                  <label for="title_edit">Enter Title</label>
                  <input type="text" class="form-control" id="title_edit" name="title_edit" aria-describedby="emailHelp" placeholder="Enter Tiltle" >
                  <!-- <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small> -->
                </div>
                <div class="form-group">
                  <label for="note_edit">Write note</label> <br>
                  <textarea name="note_edit" id="note_edit" cols="45" rows="5" class="form-control" placeholder="Write here..."></textarea>
                </div>
                <button type="submit" class="btn btn-primary my-4">Update note</button>
          </form>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>
<!-- dele modal -->
<div class="modal fade" id="exampleModalCenter" tabindex="-1" role="dialog" aria-labelledby="exampleModalCenterTitle" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLongTitle">Modal title</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
        <form action="http://localhost/cruwd.php/cruwd.php?key=delete" method="post">
          <input type="text" style="display:none;" name="sn_dele" id="sn_dele">
          <span>ARE you sure?</span>
          <button type="submit" class="btn btn-primary my-4" >OK</button>
        </form>
      </div>
      
    </div>
  </div>
</div>
 
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
            <a class="navbar-brand" href="#">Note Pad</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
              <ul class="navbar-nav">
                <li class="nav-item active">
                  <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Features</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Pricing</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link disabled" href="#">Disabled</a>
                </li>
              </ul>
            </div>
          </nav>
          
        <div class="container my-5" id="out">
            <form action="http://localhost/cruwd.php/cruwd.php?key=insert" method="post">
                <div class="form-group">
                  <label for="exampleInputEmail1">Enter Title</label>
                  <input type="text" class="form-control" id="title" name="title" aria-describedby="emailHelp" placeholder="Enter Tiltle" >
                  <!-- <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small> -->
                </div>
                <div class="form-group">
                  <label for="note">Write note</label> <br>
                  <textarea name="note" id="note" cols="45" rows="5" class="form-control" placeholder="Write here..."></textarea>
                </div>
                <button type="submit" class="btn btn-primary my-4">Add note</button>
              </form>
        </div>
        <div class="container">
        <table class="Table table" id="myTable">
            <thead>
            <tr>
                <td>Sn</td>
                <td class="col">Title</td>
                <td class="col">Notes</td>
                <td class="col">Actions</td>
            </tr>
            </thead>
            
            <tbody>
            <?php
                $sn=1;
                $sql="SELECT * FROM `notes`";
                $result=mysqli_query($conn,$sql);
                while($row=mysqli_fetch_assoc($result))
                {
                    echo "
                <tr>
                    <td>$sn</td>
                    <td class='title'>".$row['Title']."</td>
                    <td>".$row['Des']."</td>
                    <td><button class='btn btn-primary my-4 edit'>"."Edit"."</button><button class='dele btn btn-primary my-4'>"."Delete"."</button></td>
                </tr>";
                $sn+=1;
                }
                
            ?>
            </tbody>
            
                
        </table>
        </div>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js" integrity="sha384-w76AqPfDkMBDXo30jS1Sgez6pr3x5MlQ1ZAGC+nuZB+EYdgRZgiwxhTBTkF7CXvN" crossorigin="anonymous"></script>

        <script  src="https://code.jquery.com/jquery-3.6.3.min.js"></script>
         <script src="https://cdn.datatables.net/1.13.1/js/jquery.dataTables.min.js"></script>
        <script>
          $(document).ready( function () {
    $('#myTable').DataTable();
} );
        
        </script>
        <script>
  let edits=document.getElementsByClassName("edit")
  Array.from(edits).forEach(e => {
    e.addEventListener('click',()=>{
      // console.log(e.parentElement.parentElement)
      let title=e.parentElement.parentElement.getElementsByTagName("td")[2].textContent
      let note=e.parentElement.parentElement.getElementsByTagName("td")[3].textContent
      let sn=e.parentElement.parentElement.getElementsByTagName("td")[0].textContent
      // console.log(title)
      sn_edit.value=title
      title_edit.value=title   //imp
      note_edit.value=note     //imp
      
      $('#exampleModal').modal('toggle')
    })
    
  });
  
 </script>
 <script>
  let dels=document.getElementsByClassName("dele")
  Array.from(dels).forEach(e => {
    e.addEventListener('click',()=>{
      
      let title=e.parentElement.parentElement.getElementsByTagName("td")[2].textContent
      sn_dele.value=title   //imp
      console.log(sn_dele.value)
      $('#exampleModalCenter').modal('show')
    })
    
  });

 </script>
   
<script>
  let cls=document.getElementsByClassName("close")
  Array.from(cls).forEach(e => {
    e.addEventListener('click',()=>{
     
      $('#exampleModalCenter').modal('hide')
      $('#exampleModal').modal('hide')
    })
    
  });
  
</script>
        
        
  
  
  
  
  </body>
</html>
