<template>
    <div class="sidebar">
        <div class="top">
            <div class="avatar">
                <span><i class="fa fa-user icon"></i></span>
            </div>

            <div class="info">
                <p class="name">Luis henrique</p>
                <span class="status">online</span>
            </div>
        </div>

        <div class="menu">

        </div>
    </div>
</template>

<script>
export default {
    name: 'SideBarView',
}
</script>

<style lang="scss" >
.sidebar {
    .top {
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        padding: 25px 5px;

        .avatar {
            margin-right: 10px;

            span {
                display: block;
                width: 50px;
                height: 50px;
                border-radius: 50%;
                background: #ccc;
                display: flex;
                justify-content: center;
                align-items: center;
                color: #666666;
            }
        }

        .info {

            p {
                margin: 0;
                color: #fff;
            }

            .name {
                font-size: 13px;
                margin: 0;

            }

            .status {
                font-size: 10px;
                color: #fff;
            }
        }
    }
}
</style>