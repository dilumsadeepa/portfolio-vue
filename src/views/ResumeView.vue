<template>
  <NavBarVue />
  <br><br><br><br>


    <div class="container bac">
        <br><br>
        <div class="row">
            <!-- resume use -->

            <h4>RESUME <span class="nheading">-----</span></h4>
            <br><br>

            <div class="col-sm-10 resumebox">
                <h5 class="rehead">FOLLOWING BACHELOR OF INFORMATION AND COMMUNICATION TECHNOLOGY (HONOURS)</h5>
                <div class="stu">
                    2020 - Present
                </div>
                <br>
                <h6>Faculty of Technology - University of Ruhuna</h6>
                <br>
                <ul>
                    <li>Current CGPA: 2.54/4.00 (two semesters)</li>
                    <li>Member of Mentor Team in Batch 4</li>
                </ul>
            </div>

            <br>


            <div class="col-sm-10 resumebox">
                <h5 class="rehead">G C E ADVANCED LEVEL EXAMINATION</h5>
                <div class="stu">
                    2018 - completed
                </div>
                <br>
                <h6>Thalawa Maha Viduhala, Thalawa - Anuradhapura</h6>
                <br>
                <ul>
                    <li>Technology stream | 1A passes and 2C pass</li>
                    <li>President of ICT Club - 2017-2018</li>
                    <li>Mentor of Class in 2017 </li>
                    <li>Representative of ICT Subject</li>
                </ul>
            </div>
            <br>

            <div class="col-sm-10 resumebox">
                <h5 class="rehead">G C E ORDINARY LEVEL EXAMINATION</h5>
                <div class="stu">
                    2015 - completed
                </div>
                <br>
                <h6>Kekirawa Central College - Kekirawa</h6>
                <br>
                <ul>
                    <li>5A passes, 3B passes, C pass</li>
                    <li>Member of Literary Society</li>
                    
                </ul>
            </div>

            

        </div>








        <br><br>
    </div>


</template>

<script>
import NavBarVue from '../components/NavBar.vue'
export default {
    components:{
        NavBarVue
    }

}
</script>

<style>

    .bac{
        background-color: #06061c;
        color:white;
    }

    .bacrow{
        background-color: gray;
    }

    .resumebox{
        padding: 20px;
        margin: 10px;
        border-bottom: 2px solid blue;
        border-left: 5px solid gray;
    }

    .nheading{
        padding-left: 5px;
        margin-left: 10px;
        width: 150px;
        height: 2px;
        color: yellow;
    }

    .rehead{
        color: green;
    }

    .stu{
        padding: 7px;
        background-color: darkgray;
        width: 150px;
    }

</style>