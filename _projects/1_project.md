---
layout: page
title: 숙박 공유 웹 프로젝트
description: 국비 교육 중 팀 프로젝트로 진행하였던 숙박 공유 플랫폼 DB 프로젝트를 웹 사이트로써 완성시키고자 진행하였습니다.
img: assets/img/12.jpg
importance: 1
category: work
---

<a href="http://ec2-3-39-24-218.ap-northeast-2.compute.amazonaws.com:8080/">AWS EC2에 배포한 사이트로 이동하기</a>

<div class="row">
    <!--div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/airbnb.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div-->
</div>
<div class="caption">
    영상 용량 관계상 영상 로딩 및 실행 시간이 오래 걸릴 수 있습니다.
</div>

<div class="row">
    <div class="title">기술 스택</div>
</div>
<hr>
<div class="row">
    <div class="col-sm mt-2 mt-md-0">
        <div class="subtitle">FrontEnd</div>
        <ul>
            <li>JSP</li>
            <li>HTML</li>
            <li>CSS</li>
            <li>BootStrap</li>
            <li>dateRangePicker</li>
        </ul>
        <div class="subtitle">BackEnd</div>
        <ul>
            <li>Java</li>
            <li>Spring Framework</li>
            <li>MyBatis</li>
            <li>javaScript / jQuery</li>
            <li>Oracle</li>
            <li>MySQL</li>
        </ul>
    </div>
    <div class="col-sm mt-2 mt-md-0">
        <div class="subtitle">IDE</div>
        <ul>
            <li>Eclipse</li>
            <li>DBeaver</li>
            <li>MySQL WorkBench</li>
        </ul>
        <div class="subtitle">SERVER</div>
        <ul>
            <li>Tomcat 9.0</li>
            <li>AWS EC2 / linux</li>
            <li>AWS RDS</li>
        </ul>
        <div class="subtitle">API</div>
        <ul>
            <li>Kakao Map</li>
        </ul>
    </div>
</div>
<br>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/airbnb1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.html path="assets/img/6.jpg" title="example image"
    class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.html path="assets/img/11.jpg" title="example image"
    class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
