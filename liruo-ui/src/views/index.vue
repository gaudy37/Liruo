<template>
  <div class="app-container home">
    <el-row :gutter="20">
      <el-col :sm="24" :lg="24">
        <blockquote class="text-warning" style="font-size: 14px">
          烬战 - 防线坚守指令
          <br />
          <el-link
            href="https://game.bilibili.com/hjzx/"
            type="primary"
            target="_blank"
            >https://game.bilibili.com/hjzx/</el-link
          >
          <br />
          烬战 - 情报站
          <br />
          <el-link
            href="https://zh.moegirl.org.cn/index.php?title=灰烬战线&mobileaction=toggle_view_desktop"
            type="primary"
            target="_blank"
            > --> 点击进入 <-- </el-link
          >
          <br />
          前线最新消息
          <br />
          <el-link
            href="https://game.bilibili.com/hjzx/news.html"
            type="primary"
            target="_blank"
          > --> 点击进入 <-- </el-link
          >
          <br /><br />
          <h4 class="text-warning">
            注册即可获得
            <span class="text-danger">「付费概率结晶」x3000、「免费概率结晶」x7000，「三星DOLLS自选」x1、角色★3 DOLLS 重型战斗机 P-38！</span>
            <br />
            通关「新手挑战任务」中的特色玩法教学关卡，即可获得<span class="text-danger">「概率结晶」总计1500个</span>！
            <br />
            累计6日登录，<span class="text-danger">再领10连</span>！
            <br />
            累计8日登录，即可获得<span class="text-danger">★3DOLLS轻型战斗机「CW-21 恶魔」</span>！
            <br />
            新手限定卡池<span class="text-danger">首次十连必定获得一位★3DOLLS</span>。如对招募到的DOLLS阵容不满意，可再次重新获取，且<span class="text-danger">重新获取次数不受限，直至您获得满意的DOLLS为止</span>。
            <br/>
            <br/>
            <small class="heimu" title="你知道的太多了">上述均没有。钱不够，人力不足，公司暂无。感谢你的阅读</small>
          </h4>
        </blockquote>
        <hr />
      </el-col>
    </el-row>
    <el-row :gutter="20">
      <el-col :sm="24" :lg="12" style="padding-left: 20px">
        <h2>璃偌City管理系统</h2>
        <p>
          有了璃偌City管理系统，代理人可以用于管理所有玩法的DOLLS工作分配和作战指派，如出击规划、资源运输、项目探索等等。
          当然，您也可以对她进行深度定制和功能扩展，以做出更全面更适合自己的系统！
        </p>
        <p>
          <b>当前版本:</b> <span>v{{ version }}</span>
        </p>
        <p>
          <el-tag type="danger" style="margin-right: 10px">免费开源</el-tag>
          <el-tag type="success" style="margin-right: 10px">自由定制</el-tag>
        </p>
        <p>
          <el-button
            type="primary"
            size="mini"
            icon="el-icon-cloudy"
            plain
            @click="goTarget('https://gitee.com/')"
            >访问Gitee</el-button
          >
        </p>
      </el-col>

      <el-col :sm="24" :lg="12" style="padding-left: 50px">
    <el-row>
      <el-col :span="12">
        <h2>技术选型</h2>
      </el-col>
    </el-row>
    <el-row>
      <el-col :span="6">
        <h4>后端技术</h4>
        <ul>
          <li>SpringBoot</li>
          <li>Spring Security</li>
          <li>JWT</li>
          <li>MyBatis</li>
          <li>Druid</li>
          <li>Fastjson</li>
          <li>...</li>
        </ul>
      </el-col>
      <el-col :span="6">
        <h4>前端技术</h4>
        <ul>
          <li>Vue</li>
          <li>Vuex</li>
          <li>Element-ui</li>
          <li>Axios</li>
          <li>Sass</li>
          <li>Quill</li>
          <li>...</li>
        </ul>
      </el-col>
    </el-row>
  </el-col>
    </el-row>
    <el-divider />
    <el-row :gutter="20">
      <el-col :xs="24" :sm="24" :md="12" :lg="8">
        <el-card class="update-log">
          <div slot="header" class="clearfix">
            <span>联系信息</span>
          </div>
          <div class="body">
<!--            <p>-->
<!--              <i class="el-icon-s-promotion"></i> 官网：<el-link-->
<!--                href="http://www.ruoyi.vip"-->
<!--                target="_blank"-->
<!--                >http://www.ruoyi.vip</el-link-->
<!--              >-->
<!--            </p>-->
            <p>
              <i class="el-icon-user-solid"></i> QQ交流群：
              <a href="https://jq.qq.com/?_wv=1027&k=XaiMSXzX" target="_blank">
                祖国的接班人  552178432</a
              >
            </p>
            <p>
              <i class="el-icon-chat-dot-round"></i> 微信：<a
                href="javascript:;"
                >/ *璃偌</a
              >
            </p>
          </div>
        </el-card>
      </el-col>
      <el-col :xs="24" :sm="24" :md="12" :lg="8">
        <el-card class="update-log">
          <div slot="header" class="clearfix">
            <span>更新日志</span>
          </div>
          <el-collapse accordion>
            <el-collapse-item title="v1.0.1 - 2022-06-10">
              <ol>
                <li>登录界面修改优化</li>
                <li>侧边导航栏优化</li>
                <li>其他细节优化</li>
              </ol>
            </el-collapse-item>
            <el-collapse-item title="v1.0.0 - 2022-06-08">
              <ol>
                <li>璃偌City前后端分离管理系统设想雏形</li>
              </ol>
            </el-collapse-item>
          </el-collapse>
        </el-card>
      </el-col>
      <el-col :xs="24" :sm="24" :md="12" :lg="8">
        <el-card class="update-log">
          <div slot="header" class="clearfix">
            <span>代理人信息</span>
          </div>
          <div class="body">
            <img
              src="../assets/images/agent-information.jpg"
              alt="donate"
              width="100%"
            />
            <span style="display: inline-block; height: 30px; line-height: 30px"
            >还得是你嗷！</span
            >
          </div>
        </el-card>
      </el-col>
    </el-row>
  </div>
</template>

<script>
export default {
  name: "Index",
  data() {
    return {
      // 版本号
      version: "1.0.0",
    };
  },
  methods: {
    //实现网页跳转
    goTarget(href) {
      window.open(href, "_blank");
    },
  },
};
</script>

<style scoped lang="scss">
.home {
  blockquote {
    padding: 10px 20px;
    margin: 0 0 20px;
    font-size: 17.5px;
    border-left: 5px solid #ffccff;
  }
  hr {
    margin-top: 20px;
    margin-bottom: 20px;
    border: 0;
    border-top: 1px solid #eee;
  }
  .col-item {
    margin-bottom: 20px;
  }

  ul {
    padding: 0;
    margin: 0;
  }

  font-family: "open sans", "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  color: #676a6c;
  overflow-x: hidden;

  ul {
    list-style-type: none;
  }

  h4 {
    margin-top: 0px;
  }

  h2 {
    margin-top: 10px;
    font-size: 26px;
    font-weight: 100;
  }

  p {
    margin-top: 10px;

    b {
      font-weight: 700;
    }
  }

  .update-log {
    ol {
      display: block;
      list-style-type: decimal;
      margin-block-start: 1em;
      margin-block-end: 1em;
      margin-inline-start: 0;
      margin-inline-end: 0;
      padding-inline-start: 40px;
    }
  }
}
</style>

