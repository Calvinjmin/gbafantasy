
<html>
  <style>
  ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    position: fixed;
    background-color: #00a1f1;
    text-align: center;
    width: 100%;
    display: inline-block;

  }

  li {
    float: left;
  }

  li a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
  }

  li a:hover {
    background-color: #7cbb00;
  }
    body {
      background-color: #737373
    }
    h1 {
      margin-top: 0;
      margin-bottom: 0;
      margin-left: 0;
      margin-right: 0;
      font-weight: bold;
    }
  </style>
  <h1 style = "font-family:georgia,garamond,serif;font-size:45px;color:#ffffff;line height:0px"> GBA Fantasy </h1>
  <ul>
    <li><a href="gba_fantasy.html">Home</a></li>
    <li><a href="login.html">Log-In</a></li>
    <li><a href="stats.html">Add Statistics</a></li>
    <li><a href="players.html">Add Players</a></li>
  </ul>
    <br><br><br><br>
  <h1 style="color:#FFFFFF">Input Statistics</h1>

  <form id="statsForm" action="/action_page.php">
    Last Name, First Name: <input type="text" name="playerName"><br>
    <input type="button" value="Submit">
  </form>

</html>
