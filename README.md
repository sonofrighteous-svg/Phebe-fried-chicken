body{
font-family: Arial, sans-serif;
margin:0;
background:#fafafa;
}

header{
background:#d62828;
color:white;
padding:15px;
text-align:center;
}

nav{
background:#222;
padding:10px;
text-align:center;
}

nav a{
color:white;
margin:0 15px;
text-decoration:none;
font-weight:bold;
}

nav a:hover{
color:#ffd166;
}

.hero{
background:url("https://images.unsplash.com/photo-1606755962773-d324e2b1a4a7") center/cover;
height:400px;
display:flex;
align-items:center;
justify-content:center;
color:white;
font-size:40px;
font-weight:bold;
}

.container{
width:90%;
margin:auto;
padding:40px 0;
}

.food-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.food-card{
background:white;
border-radius:10px;
box-shadow:0 4px 10px rgba(0,0,0,0.1);
overflow:hidden;
}

.food-card img{
width:100%;
height:200px;
object-fit:cover;
}

.food-card h3{
padding:10px;
}

footer{
background:#111;
color:white;
text-align:center;
padding:20px;
margin-top:40px;
}
