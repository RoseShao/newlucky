1、使用图表时 ，需将expendPlugins/chart/plugins.js中的路径改为使用环境下的路径，如
chartmix.umd.min.js改为static/plugins/luckySheet/dist2/expendPlugins/chart/chartmix.umd.min.js
expendPlugins/chart/chartmix.css改为static/plugins/luckySheet/dist2/expendPlugins/chart/chartmix.css
2、关于日期公式，dayjs的插件导入不全，已补全
3、关于日期公式，dayjs的使用方法名有错误，已修改部分，遇到需要修改的，仍需修改
4、加入自定义公式ISDIMENSION（维度小计），无实际用处，仅为了业务需要
5、当前图标与项目使用图标有冲突，font-family已从iconfont改为luckyIconfont，使用时注意