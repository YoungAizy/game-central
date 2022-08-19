<template>
    <header>
        <div class="title">
            <h1><span>Ga</span><span style="color:crimson;">me</span> Central</h1>
        </div>
        <div id="header-bg">
            <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg"
                xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 1920 1080">
                <defs>
                    <linearGradient id="linear-gradient" x1="-0.5" y1="263.5" x2="1920.5" y2="263.5"
                        gradientUnits="userSpaceOnUse">
                        <stop offset="0" stop-color="#2e3192" />
                        <stop offset="1" stop-color="#1b145a" />
                    </linearGradient>
                </defs>
                <path
                    d="M1920.5.5H-.5v526s203-187,469-157,254,169,427,123,501-152,616-125,410,174.29,409,113C1919.5,421.5,1920.5.5,1920.5.5Z"
                    style="fill: url(#linear-gradient)" />
                <rect x="296" y="264" width="88" height="88" transform="translate(238.8 -139.46) rotate(35.08)"
                    style="fill: #00a99d" />
                <polygon points="686.92 398.84 634.02 414.33 594.64 396.87 577.74 339.11 662.2 314.38 686.92 398.84"
                    style="fill: #0071bc" />
                <rect x="484" y="176" width="88" height="88" style="fill: #f15a24" />
                <rect x="143" y="151" width="88" height="88" transform="translate(-61.69 89.43) rotate(-23.2)"
                    style="fill: #f7931e" />
                <rect x="67.5" y="307.5" width="57" height="57" transform="translate(101.96 -13.39) rotate(16.92)"
                    style="fill: aqua" />
                <rect x="11" y="414" width="57" height="57" transform="translate(-253.82 108.84) rotate(-36.22)"
                    style="fill: #ed1e79" />
                <rect x="-7" width="57" height="57" transform="translate(18.38 -7.06) rotate(32.02)"
                    style="fill: #0071bc" />
                <rect x="-13" y="163" width="88" height="88" transform="translate(124.61 19.79) rotate(35.08)"
                    style="fill: #00a99d" />
                <rect x="243.5" y="36.5" width="57" height="57" transform="translate(-6.5 39.55) rotate(-8.22)"
                    style="fill: aqua" />
            </svg>

        </div>
    </header>
</template>

<script>
export default {
    name: 'Header'
}
</script>


<style scoped>

header{
    position: relative;
}
.title{
    padding: 2rem 1rem;
    background-color: rgba(80, 121, 255, 0.548);
    border-bottom: 1px solid rgb(54, 42, 165);
    font-size: xx-large;
}
h1{
    margin:0;
    text-transform: uppercase;
    color:white;
}

span{
    color: cornflowerblue;
}

#header-bg{
    width: 100%;
    position:absolute;
    top: 0;
    z-index: -5;
}
</style>