<template>
  <form>
    <h2>Registration Form</h2>
      <label>First Name:</label>
      <input type="text" required>
      <label>Last Name:</label>
      <input type="text" required> 
      <label>Email:</label>
      <input type="email" required>           
      <label>Date of Birth:</label>
      <input type="date" required>
      <label>Upload Image</label>
      <input type="file" id="" name="" required>    
      <label>Address:</label>
      <input type="text" required>
      <label>Password:</label>
      <input type="password" required>              
<br>           
      <input type="submit" value="Submit">             
  </form>
</template>

<script>
export default {

}
</script>

<style>

form{
    max-width: 420px;
    margin: 30px auto;
    background: white;
    text-align: left;
    padding: 40px;
    border-radius: 10px;
}
label{
    color: #aaa;
    display: inline-block;
    margin: 25px 0 15px;
    font-size: 0.6em;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-weight: bold;
}
input{
    display: block;
    padding: 10px 6px;
    width: 100%;
    box-sizing: border-box;
    border: none;
    border-bottom: 1px solid #ddd;
    color: #555;
}
</style>