# javascript-script
probooking task
 SRC TAGS -

1.{jquery}       src="https://code.jquery.com/jquery-3.6.0.min.js"
2.{ajax}         src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"
3.{bootstrap}    src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"
4.{jquery plugin}          src="https://getprobooking.com/vendor/css/latest_website/js/jquery.sticky.js"
5.{css}           src="https://getprobooking.com/vendor/css/latest_website/js/main.js"
6.{linking}           src="https://cdn.firstpromoter.com/fpr.js" 
7.{google tag}    src="https://www.googletagmanager.com/gtag/js?id=G-KK2KS9SQNY"
8 {url}           src="https://www.facebook.com/tr?id=2895889150722117&ev=PageView&noscript=1"
9.{google tag}    src="https://www.googletagmanager.com/gtag/js?id=G-ZYMFTPOJDL"
10.{api call}     src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"




JS SCRIPT TAGS-

1. <script>(function(w){w.fpr=w.fpr||function(){w.fpr.q = w.fpr.q||[];w.fpr.q[arguments[0]=='set'?'unshift':'push'](arguments);};})(window);
   fpr("init", {cid:"w5ghzair"}); 
   fpr("click");
   </script>
2. <script type="text/javascript">
  (function(e,t){var n=e.amplitude||{_q:[],_iq:{}};var r=t.createElement("script")
  ;r.type="text/javascript"
  ;r.integrity="sha384-tzcaaCH5+KXD4sGaDozev6oElQhsVfbJvdi3//c2YvbY02LrNlbpGdt3Wq4rWonS"
  ;r.crossOrigin="anonymous";r.async=true
  ;r.src="https://cdn.amplitude.com/libs/amplitude-8.5.0-min.gz.js"
  ;r.onload=function(){if(!e.amplitude.runQueuedFunctions){
  console.log("[Amplitude] Error: could not load SDK")}}
  ;var i=t.getElementsByTagName("script")[0];i.parentNode.insertBefore(r,i)
  ;function s(e,t){e.prototype[t]=function(){
  this._q.push([t].concat(Array.prototype.slice.call(arguments,0)));return this}}
  var o=function(){this._q=[];return this}
  ;var a=["add","append","clearAll","prepend","set","setOnce","unset","preInsert","postInsert","remove"]
  ;for(var c=0;c<a.length;c++){s(o,a[c])}n.Identify=o;var u=function(){this._q=[]
  ;return this}
  ;var l=["setProductId","setQuantity","setPrice","setRevenueType","setEventProperties"]
  ;for(var p=0;p<l.length;p++){s(u,l[p])}n.Revenue=u
  ;var d=["init","logEvent","logRevenue","setUserId","setUserProperties","setOptOut","setVersionName","setDomain","setDeviceId","enableTracking","setGlobalUserProperties","identify","clearUserProperties","setGroup","logRevenueV2","regenerateDeviceId","groupIdentify","onInit","logEventWithTimestamp","logEventWithGroups","setSessionId","resetSessionId"]
  ;function v(e){function t(t){e[t]=function(){
  e._q.push([t].concat(Array.prototype.slice.call(arguments,0)))}}
  for(var n=0;n<d.length;n++){t(d[n])}}v(n);n.getInstance=function(e){
  e=(!e||e.length===0?"$default_instance":e).toLowerCase()
  ;if(!Object.prototype.hasOwnProperty.call(n._iq,e)){n._iq[e]={_q:[]};v(n._iq[e])
  }return n._iq[e]};e.amplitude=n})(window,document);

  amplitude.getInstance().init("9ca572425f863018fe3689ddfa0fc01c");
</script>

3. <script type="text/javascript">
    (function(c,l,a,r,i,t,y){
        c[a]=c[a]||function(){(c[a].q=c[a].q||[]).push(arguments)};
        t=l.createElement(r);t.async=1;t.src="https://www.clarity.ms/tag/"+i;
        y=l.getElementsByTagName(r)[0];y.parentNode.insertBefore(t,y);
    })(window, document, "clarity", "script", "9ve0gh2qrk");
</script>

4. <script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-KK2KS9SQNY');
</script>

5. <script>
!function(f,b,e,v,n,t,s)
{if(f.fbq)return;n=f.fbq=function(){n.callMethod?
n.callMethod.apply(n,arguments):n.queue.push(arguments)};
if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
n.queue=[];t=b.createElement(e);t.async=!0;
t.src=v;s=b.getElementsByTagName(e)[0];
s.parentNode.insertBefore(t,s)}(window, document,'script',
'https://connect.facebook.net/en_US/fbevents.js');
fbq('init', '2895889150722117');
fbq('track', 'PageView');
</script>

6. <script type="text/javascript">
(function(f,b){if(!b.__SV){var e,g,i,h;window.mixpanel=b;b._i=[];b.init=function(e,f,c){function g(a,d){var b=d.split(".");2==b.length&&(a=a[b[0]],d=b[1]);a[d]=function(){a.push([d].concat(Array.prototype.slice.call(arguments,0)))}}var a=b;"undefined"!==typeof c?a=b[c]=[]:c="mixpanel";a.people=a.people||[];a.toString=function(a){var d="mixpanel";"mixpanel"!==c&&(d+="."+c);a||(d+=" (stub)");return d};a.people.toString=function(){return a.toString(1)+".people (stub)"};i="disable time_event track track_pageview track_links track_forms track_with_groups add_group set_group remove_group register register_once alias unregister identify name_tag set_config reset opt_in_tracking opt_out_tracking has_opted_in_tracking has_opted_out_tracking clear_opt_in_out_tracking start_batch_senders people.set people.set_once people.unset people.increment people.append people.union people.track_charge people.clear_charges people.delete_user people.remove".split(" ");
for(h=0;h<i.length;h++)g(a,i[h]);var j="set set_once union unset remove delete".split(" ");a.get_group=function(){function b(c){d[c]=function(){call2_args=arguments;call2=[c].concat(Array.prototype.slice.call(call2_args,0));a.push([e,call2])}}for(var d={},e=["get_group"].concat(Array.prototype.slice.call(arguments,0)),c=0;c<j.length;c++)b(j[c]);return d};b._i.push([e,f,c])};b.__SV=1.2;e=f.createElement("script");e.type="text/javascript";e.async=!0;e.src="undefined"!==typeof MIXPANEL_CUSTOM_LIB_URL?
MIXPANEL_CUSTOM_LIB_URL:"file:"===f.location.protocol&&"//cdn.mxpnl.com/libs/mixpanel-2-latest.min.js".match(/^\/\//)?"https://cdn.mxpnl.com/libs/mixpanel-2-latest.min.js":"//cdn.mxpnl.com/libs/mixpanel-2-latest.min.js";g=f.getElementsByTagName("script")[0];g.parentNode.insertBefore(e,g)}})(document,window.mixpanel||[]);

// Enabling the debug mode flag is useful during implementation,
// but it's recommended you remove it for production
mixpanel.init('YOUR_TOKEN', {debug: true}); 
mixpanel.track('Sign up');
</script>

7. <script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-ZYMFTP0JDL');
</script>

8. <script>
        let index = 0;
        window.addEventListener('scroll', ()=>{
            if(document.body.getBoundingClientRect().top < index){
                document.querySelector('.site-navbar').style.filter = 'drop-shadow(0px 0px 8px rgba(0,0,0,0.1))';
            }
            else if(document.body.getBoundingClientRect().top > 0){
                document.querySelector('.site-navbar').style.filter = 'none';
                document.querySelector('.site-navbar').style.background = 'white';
            }
            index = document.body.getBoundingClientRect().top;
        })
    </script>
