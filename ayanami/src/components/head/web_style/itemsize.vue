<template>
    <div :style="svg_div_style">
        <svg aria-hidden="true" data-prefix="fas" data-icon="compress-arrows-alt" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" tabindex="-2" class="svg-inline--fa fa-compress-arrows-alt fa-w-16 layout-icon selected" data-original-title="null" :style="pull_svg_style">
            <path d="M200 288H88c-21.4 0-32.1 25.8-17 41l32.9 31-99.2 99.3c-6.2 6.2-6.2 16.4 0 22.6l25.4 25.4c6.2 6.2 16.4 6.2 22.6 0L152 408l31.1 33c15.1 15.1 40.9 4.4 40.9-17V312c0-13.3-10.7-24-24-24zm112-64h112c21.4 0 32.1-25.9 17-41l-33-31 99.3-99.3c6.2-6.2 6.2-16.4 0-22.6L481.9 4.7c-6.2-6.2-16.4-6.2-22.6 0L360 104l-31.1-33C313.8 55.9 288 66.6 288 88v112c0 13.3 10.7 24 24 24zm96 136l33-31.1c15.1-15.1 4.4-40.9-17-40.9H312c-13.3 0-24 10.7-24 24v112c0 21.4 25.9 32.1 41 17l31-32.9 99.3 99.3c6.2 6.2 16.4 6.2 22.6 0l25.4-25.4c6.2-6.2 6.2-16.4 0-22.6L408 360zM183 71.1L152 104 52.7 4.7c-6.2-6.2-16.4-6.2-22.6 0L4.7 30.1c-6.2 6.2-6.2 16.4 0 22.6L104 152l-33 31.1C55.9 198.2 66.6 224 88 224h112c13.3 0 24-10.7 24-24V88c0-21.3-25.9-32-41-16.9z"></path>
        </svg>
        <svg aria-hidden="true" data-prefix="fas" data-icon="expand" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" tabindex="-2" class="svg-inline--fa fa-expand fa-w-14 layout-icon " data-original-title="null" :style="pull_svg_style">
            <path d="M0 180V56c0-13.3 10.7-24 24-24h124c6.6 0 12 5.4 12 12v40c0 6.6-5.4 12-12 12H64v84c0 6.6-5.4 12-12 12H12c-6.6 0-12-5.4-12-12zM288 44v40c0 6.6 5.4 12 12 12h84v84c0 6.6 5.4 12 12 12h40c6.6 0 12-5.4 12-12V56c0-13.3-10.7-24-24-24H300c-6.6 0-12 5.4-12 12zm148 276h-40c-6.6 0-12 5.4-12 12v84h-84c-6.6 0-12 5.4-12 12v40c0 6.6 5.4 12 12 12h124c13.3 0 24-10.7 24-24V332c0-6.6-5.4-12-12-12zM160 468v-40c0-6.6-5.4-12-12-12H64v-84c0-6.6-5.4-12-12-12H12c-6.6 0-12 5.4-12 12v124c0 13.3 10.7 24 24 24h124c6.6 0 12-5.4 12-12z"></path>
        </svg>
        <svg aria-hidden="true" data-prefix="fas" data-icon="expand-arrows-alt" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" tabindex="-2" class="svg-inline--fa fa-expand-arrows-alt fa-w-14 layout-icon " data-original-title="null" :style="pull_svg_style">
            <path d="M448 344v112a23.94 23.94 0 01-24 24H312c-21.39 0-32.09-25.9-17-41l36.2-36.2L224 295.6 116.77 402.9 153 439c15.09 15.1 4.39 41-17 41H24a23.94 23.94 0 01-24-24V344c0-21.4 25.89-32.1 41-17l36.19 36.2L184.46 256 77.18 148.7 41 185c-15.1 15.1-41 4.4-41-17V56a23.94 23.94 0 0124-24h112c21.39 0 32.09 25.9 17 41l-36.2 36.2L224 216.4l107.23-107.3L295 73c-15.09-15.1-4.39-41 17-41h112a23.94 23.94 0 0124 24v112c0 21.4-25.89 32.1-41 17l-36.19-36.2L263.54 256l107.28 107.3L407 327.1c15.1-15.2 41-4.5 41 16.9z"></path>
        </svg>
    </div>
</template>
<script>
    export default{
        data(){
            return{
                svg_div_style:{
                    width:"100px",
                    height:"28px",
                    // backgroundColor:"pink",
                    display:"flex",
                    justifyContent: "flex-start", /* 水平起点对齐 */
                },
                pull_svg_style:{
                    //下拉图标svg的style
                    width:"17px",
                    height:"17px",
                    marginTop:"10px",
                    padding: "3px",
                    borderRadius:"5px",
                    position:"relative",
                    top:"0px",
                    border :`1px solid ${this.$root.$data.color.font}`,
                    fill:`${this.$root.$data.color.font}`,
                    marginRight:"5px"
                    
                },
            }
        }
    }
</script>