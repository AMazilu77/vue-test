<template>
  <div class="body">
    <h3 id='get'>GET: /OPTIONS/{googleId}</h3>
    <!-- <h5>options</h5> -->
  
     
      <table>
        <tr>
          <th>{platformName}</th>
          <th>{optionName}</th>
          <th>{optionValue}</th>
          <th>{dogDigitald}</th>
          <th>  </th>
        </tr>
        <tr>
          <td>data1</td>    
          <td>data1</td>
          <td>data1</td>
          <td>data1</td>
          <td>data1</td>
          <td> <button> Edit </button> </td>
        </tr>
        <tr>
          <td>data1</td>    
          <td>data1</td>
          <td>data1</td>
          <td>data1</td>
          <td>data1</td>
          <td> <button> Edit </button> </td>
        </tr>
        <tr>
          <td>data1</td>    
          <td>data1</td>
          <td>data1</td>
          <td>data1</td>
          <td>data1</td>
          <td> <button> Edit </button> </td>
        </tr>
        <tr>
          <td>data1</td>    
          <td>data1</td>
          <td>data1</td>
          <td>data1</td>
          <td>data1</td>
          <td> <button> Edit </button> </td>
        </tr>
      </table>
   
     </div>
</template>

<script>
export default {
  name: "getBody",
};


// api fetch attempt, CORS issue
const url = "https://services.metricsamsi.com/v1.0/dealers/swagger/index.html";
fetch(url, {
  method: "GET",
  mode: "cors",
  withCredentials: true,
  headers: {
    "X-Auth-Token": "81c14de2-6891-461b-9ea6-3ed218675b8f",
  },
}).then((res) => console.log(res));
//   .then(resp => resp.json())
//   .then(function(data) {
//     console.log(data);
//   })
//   .catch(function(error) {
//     console.log(error);
//   });
</script>

<style scoped>
.body {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-direction: column;
  margin-bottom: 10px;
  border: 1px;
  border-color: black;
  border-style: solid;
  background-color: rgb(236, 234, 234);
  justify-content: center;
  width: 90%;
  padding: 5%;
  columns: 1;
}

table {
    display: flex;
    justify-items: normal;
   
}

#get {
    text-decoration: underline;
}
</style>
