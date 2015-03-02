
<script>
$(document).ready(function(){
   $('.entry-title').css('display', 'none').remove();
    $('#posts').css('display', 'none').remove();
    $('.rail1CTA').css('display', 'none').remove();
    $('hr').css('display', 'none').remove();
    $('.share').css('border-bottom', '0px');
});

</script>

<style>
.entry-title {display:none;}
#posts {display:none;}
.rail1CTA {display:none;}
</style>
<div class="main-wrap">
  <div notifications=""></div>
  <main ng-view="" id="home">

  <section class="header">
 
    <img src="/static/img/pages/about/airpair.png"><b style="font-size:28px">&nbsp;&nbsp; +&nbsp;&nbsp;&nbsp;</b> <img src="http://www.ng-conf.org/images/logo.svg">
    
    <table>
      <tbody><tr>
        <td><span>{</span></td>
        <td><h2><br>
      AirPair is a <b>community</b> of <b>world class developers</b>
      <a style="text-align: center;" onclick="angular.element('#join input').focus()">claim your <b>$50 ng-conf credit</b> - sign up below</a>
    </h2></td>
        <td><span>}</span></td>
      </tr>
    </tbody></table>
  </section>


  <section id="join">

    <div cta-home-join=""><ul>
  <li><img src="//0.gravatar.com/avatar/b56bb22b3a4b83c6b534b4c114671380?s=100"></li>
  <li><img src="//0.gravatar.com/avatar/c01ef7584331527e1c600b85ba6a75f3?s=100"></li>
  <li><img src="//0.gravatar.com/avatar/892cdc57a3a64ea0ad59827bc6d1ddf7?s=100"></li>
  <li class="you nomob">
    <!-- ngIf: !session || !session.email --><b ng-if="!session || !session.email" class="ng-scope">Hello</b><!-- end ngIf: !session || !session.email -->
    <!-- ngIf: session.email -->
  </li>
  <li><img src="//0.gravatar.com/avatar/b988f05edd27e18eb63b0c5abfdc113c?s=100"></li>
  <li><img src="//0.gravatar.com/avatar/f524745bb9975ba777b5c4a9922eb614?s=100"></li>
  <li><img src="//0.gravatar.com/avatar/fbf41c66afb1e3807b7b330c2d8fcc28?s=100"></li>
</ul>


<h3>Get introduced to over 2,000 of the <b>best software experts</b> on the web</h3>

<form id="joinForm" novalidate="" name="joinForm" ng-submit="submit(joinForm.$valid, data)" class="ng-invalid ng-invalid-required ng-valid-pattern ng-valid-minlength ng-valid-email ng-dirty">

  <!-- ngIf: data.email --><div class="homeNameDiv ng-scope form-group has-error has-feedback" ng-if="data.email" form-group="">
    <input id="homeJoinName" name="name" form-control="" type="text" placeholder="Enter full name (e.g. John Smith)" ng-model="data.name" required="" ng-minlength="4" ng-pattern="/\w+ \w+/" tabindex="33212" ng-focus="focusInput(this)" ng-blur="blurInput(this)" class="ng-pristine form-control ng-invalid ng-invalid-required ng-valid-pattern ng-valid-minlength ng-touched">

    
  </div><!-- end ngIf: data.email -->

  <!-- ngIf: !data.email -->

  <button track-click="auth" data="subscribe" ng-class="data.email ? '' : 'focushide'" type="submit" class="btn btn-primary" tabindex="33214" ng-focus="focusInput(this)"><b>Join</b></button>

  <!-- ngIf: data.email --><!-- end ngIf: data.email -->

<a href="#">Actually I'm a software expert!</a>
</form>


</div>

  </section>

  <section class="how">

    <div class="vr"></div>

    <h2>How can you use AirPair?</h2>
    <br>

    <div class="row">
      <div class="col-md-4">
        <h3>Troubleshooting</h3>
        <p>AirPair attracts experts with eagle eyes to point out the problems.
        Our experts are top-notch in their stack.</p>
      </div>
      <div class="col-md-4">
        <h3>Mentorship</h3>
        <p>Having a mentor is precious, especially when it comes to sorting out
        complex problems and learning new technologies.</p>
      </div>
      <div class="col-md-4">
        <h3>Code Review</h3>
        <p>Everyone can use a second set of eyes
            with tons of experience to improve
          their code base.</p>
      </div>
    </div>
    <div class="row">
      <div class="col-md-4">
        <h3>Vetting</h3>
        <p>Building a team is hard - boost your
          confidence by having an expert on
          your side to vet potential candidates</p>
      </div>
      <div class="col-md-4">
        <h3>Advice</h3>
        <p>Enable your team to adopt new
          technologies that improve the
          long-term capabilities of your product.</p>
      </div>
      <div class="col-md-4">
        <h3>And More!</h3>
        <p>AirPair is your go-to platform when
            you need to get unstuck without
            wasting time and resources.</p>
      </div>
    </div>
  </section>

<!-- <div class="vr"></div>
<section class="gaurantee">

  <div class="block">try it out, risk free</div>
  <div class="vr" style="margin-top:-30px"></div>

  <p>We have a 100% satisfaction guarantee</p>

  <label>Warning AirPairing can become addictive once you realized how awesome it is.</label>

</section> -->

  <br><br><br>
    <br><br><br>

  </main>
</div>