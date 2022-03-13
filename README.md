body {
  margin: 0;
  padding: 0;
  overflow: hidden;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

a:before {
  content: attr(data-text);
  color: white;
  position: absolute;
  left: 20px;
  top: 20px;
  font-size: 14px;
  text-decoration: none;
}
a:hover:before {
  content: attr(data-text2);
  color: #35ebbe;
}




Resources
