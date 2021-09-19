HomeVisitApp Login 
 Welcome To Home Visit App 
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>submit demo</title>
  <style>
  p {
    margin: 0;
    color: rgba(245, 9, 194, 0.918);
  }
  div,p {
    margin-left: 10px;
  }
  span {
    color: rgb(245, 2, 164);
  }
  </style>
  <script src="https://code.jquery.com/jquery-3.5.0.js"></script>
</head>
<body>
 
<p>Type 'your agent number and your initial' to validate.</p>
<form action="javascript:alert( 'success!' );">
  <div>
    <input type="text">
    <input type="submit">
  </div>
</form>
<span></span>
 
<script>
$( "form" ).submit(function( event ) {
  if ( $( "input" ).first().val() === "A00JJ", "A01SK") {
    $( "span" ).text( "Validated..." ).show();
    return;
  }
 
  $( "span" ).text( "Not valid!" ).show().fadeOut( 1000 );
  event.preventDefault();
});
</script>
 
</body>
</html>

