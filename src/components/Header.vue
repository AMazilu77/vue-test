<template>
  <header>
    <h3 id='get' >Get: /Accounts/Google</h3>
    <div>
      <form id='dropdown' name="Google View Name">Google View Name</form>
      <!-- <label for="Google View Name"> GOOGLE VIEW NAME</label> -->
      <select name="GoogleViewName" id="GoogleView">
        Google View Name
        <option value="value 1">Option 1</option>
        <option value="value 2">Option 2</option>
      </select>
    </div>
    <div>
      <button class="btn-primary">New</button> <button>Save</button>
      <button class="btn-primary">Delete</button>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 10px;
  border: 1px;
  border-color: black;
  border-style: solid;
  background-color: rgb(236, 234, 234);
}

#dropdown {
    width: 110%;
}

h3 {
    margin: 1%;
}

button {
    margin: 1%;
}

#get {
    text-decoration: underline;
}
</style>
