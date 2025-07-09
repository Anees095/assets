<div class="container">
    <h3>Trending Now</h3>
    <img src="assets/images/images.png" width="200px" height="250px">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR3u_E5AoUWhLamMhuI0tzZGMf_wEsltzcrhw&s"  width="200px" height="250px" alt="">
    <img src="https://i.ytimg.com/vi/ShsFxGV_thk/maxresdefault.jpg"  width="200px" height="250px" alt="">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQXsQLEgIgszoOEY0YPdw5ZrIj7c9njIzEIg9UXzgbilbDbCmo4sRUr6GXAit_uTs9wKkQ&usqp=CAU"  width="200px" height="250px" alt="">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSve5A7YxUyhlHKYED_LLaRQKCuW7Kl7LFIaA&s" width="200px" height="250px" alt="">
</div>
<div class="seperation"></div>   
.container{
    height: 80vh;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
    cursor: pointer;
    transition: all 0.3s linear;
}

.container img{
border: 2px solid gray;
border-radius: 10px;
filter: blur(5px);
}
.container img:hover{
    filter: none;
    cursor: pointer;
    transform: scale(1.1);
} 
/////
.container{
    height: 80vh;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 30px;
    cursor: pointer;

}
h3{
    text-align: center;
    color: white;
    font-family: "Martel Sans", serif;
    position: relative;
    bottom: 200px;
    left: 42%;
    font-weight: bold;
    font-size: x-large;
  
}
.container img{
   
    border-radius: 10px;
    /* border: 2px solid gray; */
    position: relative;
    right: 80px;
    transition: all 0.2s linear;
}
.container img:hover{
    filter: none;
    transform: scale(1.1);
}.seperation{
    border: 2px solid gray;
    width: 100%;
}