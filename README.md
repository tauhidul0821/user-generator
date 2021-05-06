# first VueJS app , user generator 

```JS

- v-bind:src

<img v-bind:src="picture" alt="">
<img v-bind:src="picture" v-bind:alt="firstName">


<img v-bind:src="picture" v-bind:alt="`${firstName} ${lastName}`">

<img v-bind:src="picture" :alt="`${firstName} ${lastName}`">

- now we can use css class 

for ex:
<img :class="gender" v-bind:src="picture" v-bind:alt="`${firstName} ${lastName}`">

- in button add a click event 
for ex: 
<button v-on:click="getUser()" :class="gender">Get Random User</button>




```


<img width="441" alt="Screenshot 2021-04-26 at 9 50 09 PM" src="https://user-images.githubusercontent.com/58136550/116112725-a4ec5d80-a6d9-11eb-82ff-64069e2944e7.png">
<img width="440" alt="Screenshot 2021-04-26 at 9 50 17 PM" src="https://user-images.githubusercontent.com/58136550/116112733-a87fe480-a6d9-11eb-9dff-87ad3c6e3e35.png">
<img width="457" alt="Screenshot 2021-04-26 at 9 50 37 PM" src="https://user-images.githubusercontent.com/58136550/116112743-a9b11180-a6d9-11eb-9d6e-ca5694f029f9.png">
<img width="428" alt="Screenshot 2021-04-26 at 9 50 46 PM" src="https://user-images.githubusercontent.com/58136550/116112748-aae23e80-a6d9-11eb-8a05-6c0dc6899a6f.png">

## 












