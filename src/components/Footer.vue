<template>
  <div id="footer"
       class="container-fluid">

    <div class="footer-main">
      <div class="title">
        <h2>全勾教育</h2>
        <p>----------------------</p>
        <p>业务联系</p>
        <p>15800626228(张老师)</p>
      </div>
      <div class="address_tel_fax">
        <p>地址：公司地址公司地址公司地址公司地址</p>
        <p>Tel：888-888-888</p>
        <p>Fax：8888-88888888</p>
      </div>
      <div class="email_wx">
        <p>邮箱：liyunkun_11@163.com</p>
        <p>公司微信号：ilyk_gg</p>
      </div>
    </div>
    <p class="copy">Copyright &copy; 2019 - 2020 上海全勾教育科技有限公司</p>
    <div class="pBottom">

      <a href="http://www.beian.miit.gov.cn/"
         target="_blank">版权所有&nbsp;网站备案&nbsp;沪ICP备18017950号-1</a>
    </div>
  </div>
</template>
<script>
export default {
  name: "Footer",
  data () {
    return {};
  }
};
</script>
<style scoped>
#footer {
  width: 100%;
  height: 100%;
  color: #fff;
  /* background: #474747; */
  background-image: url("../assets/img/footer.png");
  background-size: cover;
  overflow: hidden;
  text-align: center;
}
.container-fluid {
  padding: 0;
}
.footer-main {
  max-width: 1200px;
  display: flex;
  justify-content: space-around;
  color: #d3d3d3;
  margin: auto;
}
.title {
  margin-bottom: 20px;
  margin-top: 20px;
  text-align: left;
}
.title h2 {
  font-size: 40px;
  margin-bottom: 40px;
}
.address_tel_fax {
  color: #d3d3d3;
  font-size: 14px;
  margin: 10px 0;
}
.email_wx {
  color: #d3d3d3;
  font-size: 14px;
}
.copy {
  color: #d3d3d3;
  font-size: 14px;
  margin: 50px 0 10px;
}
.pBottom {
  width: 100%;
  height: 40px;
  line-height: 40px;
  background-color: #000;
}
.pBottom a {
  color: #d3d3d3;
}

.pBottom a:link {
  color: #d3d3d3;
}
@media screen and (max-width: 997px) {
  .title {
    font-size: 20px;
  }
  .address_tel_fax {
    font-size: 12px;
  }
  .email_wx {
    font-size: 12px;
  }
  .copy {
    font-size: 12px;
    margin: 30px 0 10px;
  }
}
</style>

