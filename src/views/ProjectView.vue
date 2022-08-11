<template>

    <NavBarVue />
    <br><br><br><br>

    <div class="container bac">
        <br><br>
        <div class="row">

            <div class="col-sm-2">
                
            </div>

            <div class="col-sm-8">

                <div class="vgit">
                    <h2>You can view my all projects in GitHub. Click the button to view my Github Profile</h2>
                    <a href="https://github.com/dilumsadeepa" class="btn bgit">Go To GitHub</a>
                </div>
                <br><br>

                <div class="uncon">
                    <h3>This page is under contract</h3>
                    <h1>Comming Soon</h1>
                </div>

            </div>

            <div class="col-sm-2">
                
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

    .vgit{
        text-align: center;
    }

    .bgit{
        background: #1A2980;  /* fallback for old browsers */
        background: -webkit-linear-gradient(to right, #26D0CE, #1A2980);  /* Chrome 10-25, Safari 5.1-6 */
        background: linear-gradient(to right, #26D0CE, #1A2980); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
        color: white;
    }

    .bgit:hover{
        background: #cc2b5e;  /* fallback for old browsers */
        background: -webkit-linear-gradient(to right, #753a88, #cc2b5e);  /* Chrome 10-25, Safari 5.1-6 */
        background: linear-gradient(to right, #753a88, #cc2b5e); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
        color: white;
    }

    .uncon{
        text-align: center;
        animation: animate 3s linear infinite;
    }

    @keyframes animate{
        0%{
            border-left: 2px solid #1A2980;
            background: -webkit-linear-gradient(#753a88, #cc2b5e);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        25%{
            border-bottom: 2px solid #cc2b5e;
            background: -webkit-linear-gradient(#1488cc, #2b32b2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        50%{
            border-right: 2px solid #1488cc;
            background: -webkit-linear-gradient(#0f2027, #203a43);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        75%{
            border-top: 2px solid #0ced2e;
            background: -webkit-linear-gradient(#12c2e9, #f64f59);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        100%{
            border-left: 2px solid #cc2b5e;
            background: -webkit-linear-gradient(#1488cc, #2b32b2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
    }

</style>