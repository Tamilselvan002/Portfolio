# Responsive-personal_portfolio
This repository contains the code for my personal portfolio website built using HTML, CSS, and JavaScript. The portfolio showcases my skills, projects, and accomplishments, providing a glimpse into my professional journey.

# Live Demo
https://shreya6360.github.io/Responsive-personal_portfolio/ 


# Prerequisites
Before you begin, ensure you have met the following requirements: 
 
Git must be installed on your operating system.

# Run Locally
To run this project locally, run this command on your git bash:

Linux and macOS:

sudo git clone https://github.com/shreya6360/Responsive-personal_portfolio.git 

Windows:

git clone https://github.com/shreya6360/Responsive-personal_portfolio.git 

# License
This project is free to use and does not contains any license.

# codes are here
#root {
  max-width: 1280px;
  margin: 0 auto;
  padding: 2rem;
  text-align: center;
  align-items: center;
}
.head{
  top: 0%;
  display: flex;
  position: fixed;
}

.head img{
  height: 1em;
  justify-content: space-between;
  padding: 0 20px;
  width: 1em;
}

.addItems{
  display: flex;
  height: 40px;
  
}
.addItems label {
  position: absolute;
  left: -99999px;
}

.addItems input {
  border-radius: 10px;
  border: 2px solid transparent;
  border-color: none;
  width: 230px;
  padding: 10px;
  transition: border-color 0.25s;
}
.addItems input:hover{
  border: 2px solid gray;
}

.addItems input:focus{
  border: 2px solid rgb(0, 102, 255);
  outline: none;
}

.addItems button {
  border-radius: 10px;
  width: 50px;
  margin-left: 1px;
  justify-content: space-between;
  border: 2px solid transparent;
  align-items: center;
  font-size: 1em;
  font-weight: 500;
  font-family: inherit;
  background-color: #1a1a1a;
  cursor: pointer;
  transition: border-color 0.25s;
}

.addItems button:hover{
  border: 2px solid gray;
}

.addItems button:active{
  border: 2px solid blue;
}

.searchItems label {
  position: absolute;
  left: -99999px;
}

.searchItems input {
  border-radius: 10px;
  border: 2px solid transparent;
  width: 282px;
  margin-top: 10px;
  padding: 10px; 
  transition: border-color 0.25s;
}

.searchItems input:hover{
  border: 2px solid gray;
}

.searchItems input:focus{
  border: 2px solid rgb(0, 102, 255);
  outline: none;
}

ul{
  position: fixed;
  height: 328px;
  width: 310px;
  list-style: none;
  padding: 0 3px;
  overflow: hidden;
  overflow-y: scroll;
}
ul::-webkit-scrollbar{
  width: 10px;
}
ul::-webkit-scrollbar-thumb{
  background-color: rgb(68, 70, 71);
  border-radius: 10px;
  cursor: pointer;
}
ul::-webkit-scrollbar-thumb:hover{
  background-color: rgb(95, 95, 95);
}
li label{
  background-color: aliceblue;
  color: #000;
  border-radius: 2rem;
  align-items: center;
  padding: 0 10px;
  font-size: 20px;
  margin-left: 5px;
}
.on{
  top: 10px;
  font-size: 30px;
  cursor: pointer;
}
.on:hover{
  color: red;
  
}
.items{
  display: flex;
  justify-content: space-between;
  width: 280px;
}
.items input{
  height: 15px;
  width: 15px;
}
.foot{
  position: fixed;
  bottom: 0;
  margin-bottom: 0;
  top: 380px;
  margin: 0 80px;
  margin-top: 10rem;
  padding: 30px;
  text-align: center;
  align-items: center;

}

.foot .icon a{
  justify-content: space-between;
  margin-left: 10px;
}

