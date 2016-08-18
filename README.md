# forgot-password
In Part III of our User Portal Series, we will walk you through building a forgot password page. Your forgot password page is likely to receive more traffic than you may anticipate so make it as intuitive and user friendly as possible. 

## Tutorial

For detailed instructions, view Solodev's [Designing an Effective Forgot Password Page](http://www.solodev.com/blog/web-design/designing-an-effective-forgot-password-page.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/crmexw3r/).

## HTML

The forgot password page has the following basic HTML markup.
```
<div id="highlighted" class="hl-basic hidden-xs">
   <div class="container-fluid">
      <div class="row">
         <div class="col-sm-9 col-sm-offset-3 col-md-9 col-md-offset-3 col-lg-10 col-lg-offset-2">
            <h1>
               Forgot Password
            </h1>
         </div>
      </div>
   </div>
</div>

<div id="content" class="interior-page">
<div class="container-fluid">
<div class="row">
<!--Sidebar-->
<div class="col-sm-3 col-md-3 col-lg-2 sidebar equal-height interior-page-nav hidden-xs">
   <div class="dynamicDiv panel-group" id="dd.0.1.0">
      <div id="subMenu" class="panel panel-default">
         <ul class="subMenuHighlight panel-heading">
            <li class="subMenuHighlight panel-title" id="subMenuHighlight">
               <a id="li_291" class="subMenuHighlight" href=""><span>Register</span></a>
            </li>
         </ul>
         <ul class="panel-heading">
            <li class="panel-title">
               <a class="subMenu1" href=""><span class="subMenuHighlight">Forgot Password</span></a>
            </li>
         </ul>
         <ul class="panel-heading">
            <li class="panel-title">
               <a class="subMenu1" href=""><span>Login</span></a>
            </li>
         </ul>
      </div>
      <div class="item item-nopad item-noborder item-gold">
         <a style="padding: 5% 0px;" href="" class="btn btn-primary btn-block" role="button">LEARN MORE</a> 
      </div>
   </div>
</div>

<!--Content-->
<div class="col-sm-9 col-md-9 col-lg-10 content equal-height">
  <div class="content-area-right">
   <div class="content-crumb-div">
      <a href="">Home</a> / <a href="">Your Account</a> / Forgot Password
   </div>
      <div class="row">
         <div class="col-md-5 forgot-form">
            <p>
               Please enter your email address below and we will send you information to change your password.
            </p>
            <label class="label-default" for="un">Email Address</label> <input id="email_addy" name="email_addy" class="form-control" type="text"><br>
            <a id="mybad" class="btn btn-primary" role="button">RESET</a>
         </div>
         <div class="col-md-5 forgot-return" style="display:none;">
            <h3>
               Reset Password Sent
            </h3>
            <p>
               An email has been sent to your address with a reset password you can use to access your account.
            </p>
         </div>
      </div>
   </div>
</div>
```
## CSS

All necessary CSS is in forgot-password.css

## External Includes
```
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link rel="stylesheet" href="forgot-password.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```
