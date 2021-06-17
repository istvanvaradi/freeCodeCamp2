<body>
   <header class="header text-center">
<h1 id="title">  iDance class application form </h1>
<p id="description">Please fill the form below to apply to the next Dance class</p>
    </header>
<div class="container ">
 
  <form id="survey-form">
    <div class="form-group">
       <label id="name-label" for="name" >Name</label>
    <input type="text"
        name="name"
        id="name"
        class="form-control" 
        placeholder="Enter Your Name"
         required
         ></ipnut>
    </div>
  <div class="form-group">
       <label id="email-label" for="email" >Your e-mail</label>
    <input type="email"
        name="email"
        id="email"
        class="form-control"         placeholder="Email"
           required
         ></ipnut>
    </div>
  <div class="form-group">
       <label id="number-label" for="name" >Age<span class="name">(optional)<span></label>
    <input 
        type="number"
        name="age"
        id="number"
        min="10"
        max="99"
        class="form-control"
        placeholder="Age"
         ></ipnut>
    </div>
   <div id="dropdown" class="form-group">
      <label>What  is your favorite style?</label>
      <select id="dropdown" name="role" class="form-control" required>
        <option disabled selected value>hip-hop</option>
        <option value="student">Contemporary</option>
        <option value="job">Jazz</option>
        <option value="learner">Yoga</option>
        <option value="classical-balett">Classical ballet</option>
        <option value="other">Other</option>
      </select>
    </div>
    <div class="form-group" >
    <p>Would you have oonline class during the pandemic?</p>
      <label>
        <input name="user-recommend" class="input-radio" type="radio"  value="definitely no"/>Absolutely not.
      </label> <!//* pay attention you need to put text after the imput declaration*//!>
       <label>
        <input name="user-recommend" class="input-radio" type="radio"  value="Yes, sure!"/>Yes, Sure! 
      </label>
       <label>
        <input name="user-recommend" class="input-radio" type="radio"  value="not sure"/>I am not sure. 
      </label>
    </div>
    
   <div class="form-group">
     <p> Any imporvments in...?</p>
     <label>
       <input class="input-checkbox" type="checkbox" value="way of explaining"/>
      The way I explain the coreography
     </label>
      <label>
       <input class="input-checkbox" type="checkbox" value="the speed I show the routine " />
The speed I show the routine     </label> 
     <label>
       <input class="input-checkbox" type="checkbox" value="how i set the alignment of the forms" />
       How I set the alignment of the forms
     </label> 
     <label>
       <input class="input-checkbox" type="checkbox" value=" warm ups at the beggining" />
       How we do the warm ups at the beggining of eacth lesson
     </label>
   </div>
 <div class="form-group">
      <p>Any comments or suggestions?</p>
      <textarea
        id="comments"
        class="input-textarea"
        name="comment"
        placeholder="Enter your comment here..."
      ></textarea>
    </div>
    <div class="">
     <button type="submit" id="submit" class="btn btn-danger">Submit
    </div>  
    
  </form>
    </div>
</body>