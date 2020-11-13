#btnfeedback {
float: left;
position: fixed;
top: calc(90% - 28px);
right: 0; /* Left or Right */
}

#btnfeedback a {
background: #FF4500;
border-radius: 3px 0 0 3px;
box-shadow: 0 0 3px rgba(0, 0, 0, .3);
border: 3px solid #fff;
border-right: 0;
display: block;
padding: 10px 7px;
transition: all .2s ease-in-out;
}

#btnfeedback a:hover {
padding-right: 10px;  /* Left or Right */
background-color: red;
}
 

.button { 
  position: fixed;
  bottom: 0px;
  right: 0px;   
  background-color: #4CAF50; /* Green */
  border: none;
  color: white;
  padding: 10px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 12px;
  margin: 1px 1px !important;
  cursor: pointer;
  border-radius: 50%;
}
.fixmodal {
	left: auto;
    right: 0px;  /* Left or Right */
    width: auto;
    height: auto;
    top: auto;
    bottom: -28px;
	padding-left: 0px !important;
}
