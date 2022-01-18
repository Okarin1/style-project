<template>
  <div class="okarin">
    <div class="content-box">
      <h2>这是H2标题</h2>
      <p>
        这是一段测试文字，一段很长的测试P标签的文字，如果你能看完真是太棒了。这是一段测试文字，一段很长的测试P标签的文字，如果你能看完真是太棒了。这是一段测试文字，一段很长的测试P标签的文字，如果你能看完真是太棒了。
      </p>
      <blockquote><p>这里是引用文字测试，这里是引用文字测试，这里是引用文字测试</p></blockquote>

      <h3>这里是H3标题</h3>
      <p>🙄</p>

      <h2>代码块测试</h2>
      <pre><code class="language-javascript line-numbers">function Person(name, age){
  this.name = name || 'okarin';
  this.age = age || 18;
}

Person.prototype.sayHi = function(){
  console.log('Hi, I am ' + this.name + ', I am ' + this.age + ' years old');
};</code></pre>
      <h3>行内测试</h3>
      <code>stylus</code>
      <h2>链接测试</h2>
      <p>
        测试链接
        <a href="https://weibo.com/u/6331216566" target="_blank">@送报少年</a>
      </p>

      <h2>图片测试</h2>
      <p>
        <img width="200" src="@/assets/alipay.jpg" alt="支付宝打赏" />
      </p>

      <h2>容器测试</h2>
      <div class="tip">
        <p class="title">提示：</p>
        <p>这是一个提示</p>
      </div>
      <div class="warning">
        <p class="title">注意：</p>
        <p>这是一个注意</p>
      </div>
      <div class="danger">
        <p class="title">STOP</p>
        <p>危险区域，禁止通行</p>
      </div>

      <div class="details">
        <p class="title">牛顿第一定律</p>
        <p>假若施加于某物体的外力为零，则该物体的运动速度不变。</p>
        <div class="right">
          <p>
            来自
            <a href="https://zh.wikipedia.org/wiki" target="_blank">维基百科</a>
          </p>
        </div>
      </div>

      <h2>
        徽章测试
        <span class="badge badge-tip" style="vertical-align: top">new</span>
        <span class="badge badge-warning" style="vertical-align: top">old</span>
      </h2>
      <div class="footer">
        MIT Licensed | Copyright © 2022-present <a href="https://weibo.com/u/6331216566" target="_blank">@Okarin</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less"></style>
