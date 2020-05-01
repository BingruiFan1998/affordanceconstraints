<!DOCTYPE html>
<html>
    <head>
        <link href="./img/favicon.png" rel="shortcut icon"/>
        <meta charset="utf-8"/>
        <meta content="width=device-width, initial-scale=1.0, maximum-scale=1.0" name="viewport"/>
        <link href="./css/iphone-xxs2.css" rel="stylesheet" type="text/css"/>
        
    </head>
    <body style="margin: 0;
 background: rgba(240, 246, 247, 1.0);">
        <input id="anPageName" name="page" type="hidden" value="iphone-xxs2"/>
        <div class="anima-container-center-horizontal">
            <div class="iphone-xxs2-dhSIGV anima-screen anima-word-break ">
                <div class="a420-DrQMSN">
                </div>
                <img anima-src="./img/---35@1x.png" class="a351-3PJCrT" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw=="/>
                <img anima-src="./img/---32@1x.png" class="a322-S6cPIR" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw=="/>
                <img anima-src="./img/---34@1x.png" class="a343-etlqKo" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw=="/>
                <img anima-src="./img/---33@1x.png" class="a334-coxrPa" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw=="/>
                <div class="suitcase5-Ajrn8n font-class-3">
                    suitcase<br />
                </div>
                <img anima-src="./img/---72@1x.png" class="a726-6haIds" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw=="/>
                <div class="a907-yyuryf anima-flexbox-container">
                    <div class="auto-flex-Frwm14 anima-flexbox-container">
                        <div class="affordance0-Sfan0r font-class-5">
                            affordance
                        </div>
                        <div class="artvive2-rIGAnz font-class-5">
                            artvive
                        </div>
                    </div>
                    <div class="auto-flex1-GiNxqf anima-flexbox-container">
                        <div class="constraints1-L7Vo2O font-class-5">
                            constraints
                        </div>
                        <div class="historical-development3-l2vbMc font-class-5">
                            historical<br />development
                        </div>
                    </div>
                </div>
                <a href="iphone-xxs9.html">
                    <img anima-src="./img/----1@1x.png" class="a18-y2HxM3" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw=="/>
                </a>
                <a href="iphone-xxs8.html">
                    <img anima-src="./img/----1@1x.png" class="a391-l8CjZW" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw=="/>
                </a>
                <a href="iphone-xxs1.html">
                    <img anima-src="./img/----1@1x.png" class="a410-Sr2vgZ" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw=="/>
                </a>
                <a href="iphone-xxs5.html">
                    <img anima-src="./img/----1@1x.png" class="a511-9izwuD" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw=="/>
                </a>
            </div>
        </div>
        <!-- Scripts -->
        <script>
            anima_isHidden = function(e) {
                if (!(e instanceof HTMLElement)) return !1;
                if (getComputedStyle(e).display == "none") return !0; else if (e.parentNode && anima_isHidden(e.parentNode)) return !0;
                return !1;
            };
            anima_loadAsyncSrcForTag = function(tag) {
                var elements = document.getElementsByTagName(tag);
                var toLoad = [];
                for (var i = 0; i < elements.length; i++) {
                    var e = elements[i];
                    var src = e.getAttribute("src");
                    var loaded = (src != undefined && src.length > 0 && src != 'data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw==');
                    if (loaded) continue;
                    var asyncSrc = e.getAttribute("anima-src");
                    if (asyncSrc == undefined || asyncSrc.length == 0) continue;
                    if (anima_isHidden(e)) continue;
                    toLoad.push(e);
                }
                toLoad.sort(function(a, b) {
                    return anima_getTop(a) - anima_getTop(b);
                });
                for (var i = 0; i < toLoad.length; i++) {
                    var e = toLoad[i];
                    var asyncSrc = e.getAttribute("anima-src");
                    e.setAttribute("src", asyncSrc);
                }
            };
            anima_pauseHiddenVideos = function(tag) {
                var elements = document.getElementsByTagName("video");
                for (var i = 0; i < elements.length; i++) {
                    var e = elements[i];
                    var isPlaying = !!(e.currentTime > 0 && !e.paused && !e.ended && e.readyState > 2);
                    var isHidden = anima_isHidden(e);
                    if (!isPlaying && !isHidden && e.getAttribute("autoplay") == "autoplay") {
                        e.play();
                    } else if (isPlaying && isHidden) {
                        e.pause();
                    }
                }
            };
            anima_loadAsyncSrc = function(tag) {
                anima_loadAsyncSrcForTag("img");
                anima_loadAsyncSrcForTag("iframe");
                anima_loadAsyncSrcForTag("video");
                anima_pauseHiddenVideos();
            };
            var anima_getTop = function(e) {
                var top = 0;
                do {
                    top += e.offsetTop || 0;
                    e = e.offsetParent;
                } while (e);
                return top;
            };
            anima_loadAsyncSrc();
            anima_old_onResize = window.onresize;
            anima_new_onResize = undefined;
            anima_updateOnResize = function() {
                if (anima_new_onResize == undefined || window.onresize != anima_new_onResize) {
                    anima_new_onResize = function(x) {
                        if (anima_old_onResize != undefined) anima_old_onResize(x);
                        anima_loadAsyncSrc();
                    };
                    window.onresize = anima_new_onResize;
                    setTimeout(function() {
                        anima_updateOnResize();
                    }, 3000);
                }
            };
            anima_updateOnResize();
            setTimeout(function() {
                anima_loadAsyncSrc();
            }, 200);
        </script>
        <!-- End of Scripts -->
    </body>
</html>
