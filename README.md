 <script>
    window.$docsify = {
      name: 'Spring Security Study',//侧边栏标题
      repo: '',//github地址
      loadSidebar: true, // 加载自定义侧边栏
      maxLevel: 4, // 默认情况下会抓取文档中所有标题渲染成目录，可配置最大支持渲染的标题层级。
      subMaxLevel: 5, // 生成目录的最大层级
      mergeNavbar: true, // 小屏设备下合并导航栏到侧边栏
      alias: { // 定义路由别名，可以更自由的定义路由规则。 支持正则
        '/.*/_sidebar.md': '/_sidebar.md'//防止意外回退
      },
    coverpage: true//设置封面
    }
  </script>

