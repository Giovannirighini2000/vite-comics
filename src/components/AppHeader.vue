<template>
    <header class="container">
        <div class="flex center-items pad-header">
            <img src="/img/dc-logo.png" alt="">
            <nav>
                <ul class="flex justify-content-list">
                    <li class="upsize relative-line bold">
                        <a href="">Characters</a>
                    </li>
                    <li class="upsize relative-line  bold">
                        <a class="active" href="">comics</a>
                    </li>
                    <li class="upsize relative-line bold">
                        <a href="">movies</a>
                    </li>
                    <li class="upsize relative-line bold">
                        <a href="">tv</a>
                    </li>
                    <li class="upsize relative-line bold">
                        <a href="">games</a>
                    </li>
                    <li class="upsize relative-line bold">
                        <a href="">collectibles</a>
                    </li>
                    <li class="upsize relative-line bold">
                        <a href="">videos</a>
                    </li>
                    <li class="upsize relative-line bold">
                        <a href="">fans</a>
                    </li>
                    <li class="upsize relative-line bold">
                        <a href="">news</a>
                    </li>
                    <li class="upsize relative-line bold">
                        <a href="">shop</a>
                    </li>
                </ul>
            </nav>


        </div>
    </header>
</template>
<script>
export default {

}
</script>
<style lang="scss"> 
.justify-content-list {
     gap: 10px;

 }

 .active {
     color: #2a92fa;
 }

 .active:after {
     content: "";
     position: absolute;
     top: 59px;
     left: 0;
     right: 0;
     height: 0.5em;
     border-bottom: 3px solid #2a92fa;

 }

 .pad-header {
     padding-top: 10px;
     padding-bottom: 10px;
 }

 .bold {
     font-weight: bold;
 }

 .relative-line {
     position: relative;
 }</style>