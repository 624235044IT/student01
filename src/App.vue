<template>
  <div id="app">
    <Students v-bind:students1="students" />
  </div>
</template>


<script>
import Students from "./components/Students.vue";

export default {
  name: "App",
  components: {
    Students,
  },
  data() {
    return {
      students: [
        {
          studentId: "624235044",
          FistName: "Niracha",
          LastName: "Wanchitnai",
          weight: 45,
          height: 155,
          picture:
            "https://raw.githubusercontent.com/624235044IT/picture/main/5.jpg",
        },
        {
          studentId: "624235034",
          FistName: "Wirakran",
          LastName: "Somjan",
          weight: 43,
          height: 165,
          picture:
            "https://raw.githubusercontent.com/624235044IT/picture/main/1.jpg",
        },
        {
          studentId: "624235051",
          FistName: "Yada",
          LastName: "banlatah",
          weight: 62,
          height: 165,
          picture:
            "https://raw.githubusercontent.com/624235044IT/picture/main/2.jpg",
        },
        {
          studentId: "624235036",
          FistName: "Kuasawan",
          LastName: "Kuji",
          weight: 65,
          height: 175,
          picture:
            "https://raw.githubusercontent.com/624235044IT/picture/main/4.jpg",
        },
        {
          studentId: "624235048",
          FistName: "Warinton",
          LastName: "Khogjan",
          weight: 65,
          height: 175,
          picture:
           "https://raw.githubusercontent.com/624235044IT/picture/main/3.jpg",
        },
      ],
    };
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>