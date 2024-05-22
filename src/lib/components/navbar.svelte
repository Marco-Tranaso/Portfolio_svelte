<ul>
    <li><a class="active" href="https://marco-tranaso.github.io/Portfolio_svelte/">Home</a></li>
    <li><a href="./2020-2021">2020-2021</a></li>
    <li><a href="./2021-2022">2021-2022</a></li>
    <li><a href="./2022-2023">2022-2023</a></li>
    <li><a href=".2023-2024">2023-2024</a></li>
  </ul>

  <style>
    ul {
    display: flex;
    justify-content: space-between;
      list-style-type: none;
      margin: 0;
      padding: 0;
      overflow: hidden;
      background-color: #333;
  } 
  
  li {
      float: left;
  }
  
  li a, .dropbtn {
      display: inline-block;
      color: white;
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
      border-radius: 5px;
      transition: background-color 0.3s;
  }
  
  li a:hover, .dropdown:hover .dropbtn {
      background-color: red;
  }
  
  li.dropdown {
      display: inline-block;
  }
  
  .dropdown-content {
      display: none;
      position: absolute;
      background-color:#333;
      min-width: 160px;
      box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  }
  
  .dropdown-content a {
      color: white;
      padding: 12px 16px;
      text-decoration: none;
      display: block;
      text-align: left;
  }
  
  .dropdown-content a:hover {background-color: red}
  
  .dropdown:hover .dropdown-content {
      display: block;
  }
  </style>