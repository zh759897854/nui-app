# nui-app
nui-APP学习笔记
## 动态的添加class绑定的数值 upx不起作用 
    export default {
        computed: {
            halfWidth() {
                return uni.upx2px(750 / 2) + 'px';
            }
        }
    }
