# bootstrap-angular
angular5 how to use bootstrap 4.0.0

有两种方法来使用bootstrap， 直接使用bootstrap的css或scss

css使用项目
ng new bootstrap-form 或ng new bootstrap-form
项目的目录下：
styles.css 文件
/* You can add global styles to this file, and also import other style files */
@import url('https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css');


scss使用项目
ng new bootstrap-scss-form --style=scss
项目的目录下： 
styles.scss 文件
/* You can add global styles to this file, and also import other style files */
@import "./app/shared/style/bootstrap/scss/bootstrap";

bootstrap官网： http://getbootstrap.com/

下载 bootstrap-4.0.0.zip
解压拷贝scss目录，到bootstrap-scss-form\src\app\shared\style\bootstrap下



实例代码：

<!--The content below is only a placeholder and can be replaced.-->
<div class="container">
  <h1> alert </h1>

  <div class="alert alert-primary" role="alert"> this is alert alert-primary! </div>
  <div class="alert alert-secondary" role="alert"> This is alert alert-secondary! </div>
  <div class="alert alert-success" role="alert"> This is a success alert-success! </div>
  <div class="alert alert-danger" role="alert"> This is a danger alert-danger! </div>
  <div class="alert alert-warning" role="alert"> This is a warning alert-warning! </div>
  <div class="alert alert-info" role="alert"> This is a info alert-info! </div>
  <div class="alert alert-light" role="alert"> This is a light alert-light! </div>
  <div class="alert alert-dark" role="alert"> This is a dark alert-dark! </div>
  <div class="alert alert-primary" role="alert">
</div>
  




