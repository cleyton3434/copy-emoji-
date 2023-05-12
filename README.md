# copy-emoji-
atalho pra copiar emoji do zap
url : https://pt.piliapp.com/emoji/list/



<!DOCTYPE html>
<html lang="pt" class="desktop classic   emojable ">
    <head>
        <meta charset="utf-8"/>
        <script>
            var ts = new Date() * 1;
        </script>
        <script>
            var LS = {};
            try {
                LS = window.localStorage;
            } catch (e) {}
            ;</script>
        <script>
            if (LS.key)
                document.documentElement.className += ' localstorage';
        </script>
        <script>
            if (navigator.userAgent.match(/(iPhone|iPod)/))
                document.documentElement.className += ' iphone';
        </script>
        <script>
            if (navigator.userAgent.match(/(Windows)/))
                document.documentElement.className += ' windows';
        </script>
        <script>
            var TWEMOJI_CDN = 'https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0'
              , TWEMOJI_CDN2 = 'https://twemoji.maxcdn.com/v/14.0.0'
              , TWEMOJI_CDN2_PATTERN = new RegExp('(no-match)');
        </script>
        <script>
            var SKIN = ''
              , DIVERSITY_LIST = '1faf6,1f450,1f932,1f64c,1f44f,1f64f,1f91d,1f44d,1f44e,1f44a,270a,1f91b,1f91c,1f91e,270c,1faf0,1f918,1f91f,1f44c,1f90c,1f90f,1f448,1faf3,1faf4,1f449,1f446,1f447,261d,270b,1f91a,1f590,1f596,1f44b,1f919,1faf2,1faf1,1f4aa,1f595,1faf5,270d,1f933,1f485,1f9b5,1f9b6,1f442,1f9bb,1f443,1f476,1f467,1f9d2,1f466,1f469,1f9d1,1f468,1f469-200d-1f9b1,1f9d1-200d-1f9b1,1f468-200d-1f9b1,1f469-200d-1f9b0,1f9d1-200d-1f9b0,1f468-200d-1f9b0,1f471-200d-2640-fe0f,1f471,1f471-200d-2642-fe0f,1f469-200d-1f9b3,1f9d1-200d-1f9b3,1f468-200d-1f9b3,1f469-200d-1f9b2,1f9d1-200d-1f9b2,1f468-200d-1f9b2,1f9d4-200d-2640-fe0f,1f9d4,1f9d4-200d-2642-fe0f,1f475,1f9d3,1f474,1f472,1f473-200d-2640-fe0f,1f473,1f473-200d-2642-fe0f,1f9d5,1f47c,1f478,1fac5,1f934,1f470,1f470-200d-2640-fe0f,1f470-200d-2642-fe0f,1f935-200d-2640-fe0f,1f935,1f935-200d-2642-fe0f,1f647-200d-2640-fe0f,1f647,1f647-200d-2642-fe0f,1f481-200d-2640-fe0f,1f481,1f481-200d-2642-fe0f,1f645-200d-2640-fe0f,1f645,1f645-200d-2642-fe0f,1f646-200d-2640-fe0f,1f646,1f646-200d-2642-fe0f,1f937-200d-2640-fe0f,1f937,1f937-200d-2642-fe0f,1f64b-200d-2640-fe0f,1f64b,1f64b-200d-2642-fe0f,1f926-200d-2640-fe0f,1f926,1f926-200d-2642-fe0f,1f9cf-200d-2640-fe0f,1f9cf,1f9cf-200d-2642-fe0f,1f64e-200d-2640-fe0f,1f64e,1f64e-200d-2642-fe0f,1f64d-200d-2640-fe0f,1f64d,1f64d-200d-2642-fe0f,1f487-200d-2640-fe0f,1f487,1f487-200d-2642-fe0f,1f486-200d-2640-fe0f,1f486,1f486-200d-2642-fe0f,1f930,1fac4,1fac3,1f931,1f469-200d-1f37c,1f9d1-200d-1f37c,1f468-200d-1f37c,1f9ce-200d-2640-fe0f,1f9ce,1f9ce-200d-2642-fe0f,1f9cd-200d-2640-fe0f,1f9cd,1f9cd-200d-2642-fe0f,1f483,1f57a,1f46b,1f46d,1f46c,1f9d1-200d-1f91d-200d-1f9d1,1f469-200d-2764-fe0f-200d-1f468,1f469-200d-2764-fe0f-200d-1f469,1f491,1f468-200d-2764-fe0f-200d-1f468,1f469-200d-2764-fe0f-200d-1f48b-200d-1f468,1f469-200d-2764-fe0f-200d-1f48b-200d-1f469,1f48f,1f468-200d-2764-fe0f-200d-1f48b-200d-1f468,26f7,1f3c2,1f3cb-fe0f-200d-2640-fe0f,1f3cb,1f3cb-fe0f-200d-2642-fe0f,1f938-200d-2640-fe0f,1f938,1f938-200d-2642-fe0f,26f9-fe0f-200d-2640-fe0f,26f9,26f9-fe0f-200d-2642-fe0f,1f93e-200d-2640-fe0f,1f93e,1f93e-200d-2642-fe0f,1f9d7-200d-2640-fe0f,1f9d7,1f9d7-200d-2642-fe0f,1f3cc-fe0f-200d-2640-fe0f,1f3cc,1f3cc-fe0f-200d-2642-fe0f,1f9d8-200d-2640-fe0f,1f9d8,1f9d8-200d-2642-fe0f,1f9d6-200d-2640-fe0f,1f9d6,1f9d6-200d-2642-fe0f,1f3c4-200d-2640-fe0f,1f3c4,1f3c4-200d-2642-fe0f,1f3ca-200d-2640-fe0f,1f3ca,1f3ca-200d-2642-fe0f,1f93d-200d-2640-fe0f,1f93d,1f93d-200d-2642-fe0f,1f6a3-200d-2640-fe0f,1f6a3,1f6a3-200d-2642-fe0f,1f3c7,1f6b4-200d-2640-fe0f,1f6b4,1f6b4-200d-2642-fe0f,1f6b5-200d-2640-fe0f,1f6b5,1f6b5-200d-2642-fe0f,1f939-200d-2640-fe0f,1f939,1f939-200d-2642-fe0f,1f46e-200d-2640-fe0f,1f46e,1f46e-200d-2642-fe0f,1f469-200d-1f692,1f9d1-200d-1f692,1f468-200d-1f692,1f477-200d-2640-fe0f,1f477,1f477-200d-2642-fe0f,1f469-200d-1f3ed,1f9d1-200d-1f3ed,1f468-200d-1f3ed,1f469-200d-1f527,1f9d1-200d-1f527,1f468-200d-1f527,1f469-200d-1f33e,1f9d1-200d-1f33e,1f468-200d-1f33e,1f469-200d-1f373,1f9d1-200d-1f373,1f468-200d-1f373,1f469-200d-1f3a4,1f9d1-200d-1f3a4,1f468-200d-1f3a4,1f469-200d-1f3a8,1f9d1-200d-1f3a8,1f468-200d-1f3a8,1f469-200d-1f3eb,1f9d1-200d-1f3eb,1f468-200d-1f3eb,1f469-200d-1f393,1f9d1-200d-1f393,1f468-200d-1f393,1f469-200d-1f4bc,1f9d1-200d-1f4bc,1f468-200d-1f4bc,1f469-200d-1f4bb,1f9d1-200d-1f4bb,1f468-200d-1f4bb,1f469-200d-1f52c,1f9d1-200d-1f52c,1f468-200d-1f52c,1f469-200d-1f680,1f9d1-200d-1f680,1f468-200d-1f680,1f469-200d-2695-fe0f,1f9d1-200d-2695-fe0f,1f468-200d-2695-fe0f,1f469-200d-2696-fe0f,1f9d1-200d-2696-fe0f,1f468-200d-2696-fe0f,1f469-200d-2708-fe0f,1f9d1-200d-2708-fe0f,1f468-200d-2708-fe0f,1f482-200d-2640-fe0f,1f482,1f482-200d-2642-fe0f,1f977,1f575-fe0f-200d-2640-fe0f,1f575,1f575-fe0f-200d-2642-fe0f,1f936,1f9d1-200d-1f384,1f385,1f574-fe0f-200d-2640-fe0f,1f574,1f574-fe0f-200d-2642-fe0f,1f9b8-200d-2640-fe0f,1f9b8,1f9b8-200d-2642-fe0f,1f9b9-200d-2640-fe0f,1f9b9,1f9b9-200d-2642-fe0f,1f9d9-200d-2640-fe0f,1f9d9,1f9d9-200d-2642-fe0f,1f9dd-200d-2640-fe0f,1f9dd,1f9dd-200d-2642-fe0f,1f9da-200d-2640-fe0f,1f9da,1f9da-200d-2642-fe0f,1f9dc-200d-2640-fe0f,1f9dc,1f9dc-200d-2642-fe0f,1f9db-200d-2640-fe0f,1f9db,1f9db-200d-2642-fe0f,1f6b6-200d-2640-fe0f,1f6b6,1f6b6-200d-2642-fe0f,1f469-200d-1f9af,1f9d1-200d-1f9af,1f468-200d-1f9af,1f3c3-200d-2640-fe0f,1f3c3,1f3c3-200d-2642-fe0f,1f469-200d-1f9bc,1f9d1-200d-1f9bc,1f468-200d-1f9bc,1f469-200d-1f9bd,1f9d1-200d-1f9bd,1f468-200d-1f9bd,1f6c0,1f6cc'.split(',')
              , SKINS = "1f3fb,1f3fc,1f3fd,1f3fe,1f3ff".split(',');
        </script>
        <script>
            var EMOJI_SIZE = 24
              , IS_TOUCH = !!0
              , SUPPORT_EMOJI = !!1
              , MOBILE_DEVICE = 'desktop classic';
        </script>
        <script>
            (typeof Object.assign == 'function') || document.write(unescape("%3Cscript%20src%3D%22%2F%2Fassets.piliapp.com%2Fs3pxy%2Fpolyfill%2Fobject_assign.min.js%22%3E%3C%2Fscript%3E"));
        </script>
        <script type="text/javascript">
            window.patch_emoji = function(e, t) {
                void 0 === t && (t = {}),
                t = Object.assign({
                    innerHTML: !1,
                    append_css: "",
                    append_class: "",
                    force: !1,
                    size: !1
                }, t);
                location.host.indexOf("dev");
                var n = location.href
                  , i = 0 < navigator.userAgent.indexOf("Windows") || 0 < n.indexOf("win=1")
                  , c = 0 < n.indexOf("forcepatch")
                  , d = (n.indexOf("nopatch=1"),
                []);
                if (document.querySelector(e)) {
                    var e = document.querySelectorAll(e)
                      , a = e[0].parentNode;
                    if (0 < n.indexOf("nopatch=1"))
                        return a.classList.remove("pathcing");
                    function o(e, n) {
                        var a = document.createElement("span")
                          , e = (a.innerHTML = "&#x" + e,
                        a.className = "emoji",
                        n.appendChild(a),
                        a.offsetWidth);
                        return a.parentNode.removeChild(a),
                        e
                    }
                    a.classList.add("patching");
                    var r = o("1f600", a)
                      , s = o("fffff", a);
                    Array.prototype.forEach.call(e, function(e) {
                        var n = e.className.match(/emoji([^ ]+)/)[1]
                          , a = e.offsetWidth;
                        (t.force || c || 1.2 * r < a || a == s || i && 0 < n.indexOf("-20e3") || i && n.match(/^1f1[ef]/)) && (t.append_class && e.classList.add(t.append_class),
                        !1 !== t.innerHTML && (e.innerHTML = t.innerHTML),
                        a = (n.match(TWEMOJI_CDN2_PATTERN) ? TWEMOJI_CDN2 : TWEMOJI_CDN) + "/72x72/",
                        -1 === (e = n).indexOf("-200d-") && (e = e.replace("-fe0f", "")),
                        n = ".emoji" + n + "{background-image:url(" + a + e + ".png);background-size:" + (t.size || r) + "px;" + (t.append_css || "") + "}",
                        d.push(n))
                    }),
                    0 < d.length && (n = document.getElementsByTagName("head")[0],
                    (e = document.createElement("style")).appendChild(document.createTextNode(d.join("\n"))),
                    n.appendChild(e)),
                    a.classList.remove("patching")
                }
            }
            ;
        </script>
        <script type="text/javascript">
            var patch_params = {
                append_css: "border: dashed gray 1px !important;margin: 0 !important;background-repeat:no-repeat;text-indent:-999em;background-position: center;",
                size: EMOJI_SIZE
            };
            !function(a) {
                navigator.userAgent.match(/(iPhone|iPad)/) && (a.append_css += "display:none;")
            }(patch_params);
        </script>
        <script type="text/javascript">
            function lister(e, i) {
                var a = "people" !== e;
                document.documentElement.classList.contains("windows") && "flags" === e ? gen_emoji_css(e, '.emojis[data-cat="' + e + '"]') : i ? a || (init_emoji('.emojis[data-cat="' + e + '"] .emoji', {
                    inline: i
                }),
                patch_emoji('.emojis[data-cat="' + e + '"] .emoji', patch_params)) : (a || init_emoji('.emojis[data-cat="' + e + '"] .emoji', {
                    inline: i
                }),
                gen_emoji_css(e, '.emojis[data-cat="' + e + '"]')),
                a && set_block_size(".emojis[data-cat='" + e + "']", "emoji emoji", "emojinone")
            }
        </script>
        <style>
            .emojisprite #cat-list .emoji {
                background-size: 24px;
                background-position: 0 0;
            }

            .emojisprite #cat-list .emoji1f600 {
                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/svg/1f600.svg);
            }

            .emojisprite #cat-list .emoji1f436 {
                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/svg/1f436.svg);
            }

            .emojisprite #cat-list .emoji1f34f {
                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/svg/1f34f.svg);
            }

            .emojisprite #cat-list .emoji26bd {
                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/svg/26bd.svg);
            }

            .emojisprite #cat-list .emoji1f697 {
                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/svg/1f697.svg);
            }

            .emojisprite #cat-list .emoji231a {
                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/svg/231a.svg);
            }

            .emojisprite #cat-list .emoji262e {
                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/svg/262e.svg);
            }

            .emojisprite #cat-list .emoji1f6a9 {
                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/svg/1f6a9.svg);
            }

            #skin-list .emoji1f469 {
                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/svg/1f469.svg);
            }

            #skin-list .emoji1f469-1f3fb {
                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/svg/1f469-1f3fb.svg);
            }

            #skin-list .emoji1f469-1f3fc {
                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/svg/1f469-1f3fc.svg);
            }

            #skin-list .emoji1f469-1f3fd {
                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/svg/1f469-1f3fd.svg);
            }

            #skin-list .emoji1f469-1f3fe {
                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/svg/1f469-1f3fe.svg);
            }

            #skin-list .emoji1f469-1f3ff {
                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/svg/1f469-1f3ff.svg);
            }
        </style>
        <script type="text/javascript">
            !function(e, t) {
                if (-1 === t.indexOf("MSIE")) {
                    for (var n = e[unescape("%68%6F%73%74")].split(".").reverse()[1], o = 0, i = 0, r = n.length; i < r; i++)
                        o += n.charCodeAt(i);
                    o % 50 != 1 && document.write(unescape("%3Cstyle%20type%3D%22text/css%22%3E.emoji%20%7Bbackground-position%3A%201987px%200%20%21important%7D%3C/style%3E"))
                }
            }(location, navigator.userAgent);
        </script>
        <script type="text/javascript">
            function lazydom(n, t, e) {
                var r;
                void 0 === e && (e = 0),
                "IntersectionObserverEntry"in window && IntersectionObserverEntry.prototype.hasOwnProperty("isIntersecting") ? (r = new IntersectionObserver(function(n) {
                    n.map(function(n) {
                        n.isIntersecting && (n.target.active_dom = function() {}
                        ,
                        t(n.target),
                        r.unobserve(n.target))
                    })
                }
                ,{
                    rootMargin: parseInt(100 * e) + "% 0px"
                }),
                [].forEach.call(n, function(n) {
                    r.observe(n),
                    n.active_dom = function() {
                        r.unobserve(n),
                        t(n)
                    }
                })) : [].forEach.call(n, function(n) {
                    n.active_dom = function() {}
                    ,
                    t(n)
                })
            }
        </script>
        <script type="text/javascript">
            function gen_emoji_css(e, n) {
                void 0 === n && (n = "#" + e);
                var n = document.querySelector(n).innerHTML
                  , i = n.split("emoji emoji").length - 1
                  , o = []
                  , d = SPRITE_BASE + "/s" + EMOJI_SIZE + "@" + DPR + "-" + e + ".png"
                  , t = "background-size:" + (1 + i) * EMOJI_SIZE + "px " + 2 * EMOJI_SIZE + "px;"
                  , a = (void 0 === window._generated_id_list && (window._generated_id_list = []),
                window._generated_id_list)
                  , e = (n.match(/emoji emoji([\w\-]+)/g).forEach(function(e, n) {
                    e = e.replace("emoji emoji", "");
                    "none" !== e && -1 === a.indexOf(e) && (a.push(e),
                    o.push(".emoji" + e + "{background-image:url(" + d + ");background-position:-" + EMOJI_SIZE * (1 + n) + "px 0;" + t + "}"))
                }),
                o = o.join("\n"),
                document.getElementsByTagName("head")[0])
                  , i = document.createElement("style");
                i.appendChild(document.createTextNode(o)),
                e.appendChild(i)
            }
        </script>
        <script type="text/javascript">
            !function(e, n) {
                if (-1 === n.indexOf("MSIE")) {
                    for (var i = e[unescape("%68%6F%73%74")].split(".").reverse()[1], o = 0, r = 0, t = i.length; r < t; r++)
                        o += i.charCodeAt(r);
                    o % 50 != 1 && (window.SPRITE_BASE = "/1.gif#")
                }
            }(location, navigator.userAgent);
        </script>
        <script type="text/javascript">
            function set_block_size(t, e, i) {
                var n, t = document.querySelector(t), r = t.offsetHeight, o = t.offsetWidth, s = t.innerHTML, e = s.split(e).length - 1, a = (g = t.querySelector("*"),
                a = g.offsetWidth,
                n = g.offsetHeight,
                g = getComputedStyle(g),
                [a += parseInt(g.marginLeft) + parseInt(g.marginRight), n += parseInt(g.marginTop) + parseInt(g.marginBottom)]), g = (void 0 !== i && (e -= s.split(i).length - 1),
                Math.ceil(e / parseInt(o / a[0])));
                t.style.height = r * g + "px"
            }
        </script>
        <script type="text/javascript">
            !function(e) {
                e.documentElement.classList.add("al-" + (navigator.language || ""));
                var a = e.createElement("style")
                  , t = e.getElementsByTagName("head")[0];
                a.type = "text/css",
                a.appendChild(e.createTextNode(".al-zh-CN .emoji1f1f9-1f1fc{display:none !important;}")),
                t.appendChild(a)
            }(document);
        </script>
        <script type="text/javascript">
            !function() {
                if (!(0 < location.href.indexOf("nohidedesc"))) {
                    var o, n = {};
                    try {
                        n = window.localStorage
                    } catch (e) {}
                    "undefined" != typeof HIDE_DESC_SELECTOR && (o = function(e) {
                        function t(e) {
                            console.log("visit 9"),
                            n.key && n.setItem("emoji-visit", 9),
                            document.removeEventListener("click", o)
                        }
                        for (var i = e.target; i && i != this && i.matches; i = i.parentNode)
                            if (i.matches(HIDE_DESC_SELECTOR)) {
                                t.call(i, e);
                                break
                            }
                    }
                    ,
                    document.addEventListener("click", o));
                    function e(e) {
                        e = ("; " + document.cookie).split("; " + e + "=");
                        if (2 == e.length)
                            return e.pop().split(";").shift()
                    }
                    function t() {
                        document.documentElement.className += " hide-desc"
                    }
                    var i = e("fb_symbol_visit") || 0
                      , c = e("tts_visit") || 0;
                    5 < Math.max(i, c) ? t() : !n.key || (i = parseInt(window.localStorage.getItem("emoji-visit")) || 0,
                    2 < ++i) ? t() : window.localStorage.setItem("emoji-visit", i)
                }
            }();
        </script>
        <script>
            var SPRITE_BASE = "//assets.piliapp.com/s3pxy/emoji/twemoji/14.0.0";
            var _DPR = window.devicePixelRatio || 1
              , DPR = 1;
            [1.5, 2].filter(function(v) {
                if (_DPR >= v)
                    DPR = v;
            });
        </script>
        <script type="text/javascript">
            function rd_add_qs(e) {
                var n = window.location
                  , o = n.search
                  , d = window.filtered_qs || []
                  , d = 0 < d.length ? "&" + d.join("&") : ""
                  , a = n.pathname + (o ? o + "&" : "?") + e + d + n.hash;
                -1 === o.indexOf(e) && ((adsbygoogle = window.adsbygoogle || []).pauseAdRequests = 1,
                window.gpt_pauseads = !0,
                document.documentElement.style.display = "none",
                setTimeout(function() {
                    n.replace(a)
                }, 0))
            }
        </script>
        <script type="text/javascript">
            function cdnjs_fallback() {
                window.nocdnjs = 1,
                rd_add_qs("nocdnjs=1")
            }
        </script>
        <link onerror="cdnjs_fallback()" rel="stylesheet" type="text/css" href="//cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/2.3.1/css/bootstrap.min.css"/>
        <link rel="stylesheet" type="text/css" href="//pt.piliapp.com/assets/v3/ntwax_5coop.css"/>
        <script>
            String.fromCodePoint || document.write(unescape("%3Cscript%20src%3D%22%2F%2Fassets.piliapp.com%2Fs3pxy%2Fpolyfill%2Fstring_fromcodepoint.min.js%22%3E%3C%2Fscript%3E"));
        </script>
        <script type="text/javascript">
            !function() {
                var t = location.host.split(".").slice(-2).join("").split("").reduce(function(t, n) {
                    return t + n.charCodeAt(0)
                }, 0)
                  , n = Math.pow;
                t === n(2, 10) + n(7, 2) - Math.floor(Math.PI) ? window.init_emoji = function(t, o) {
                    void 0 === o && (o = {});
                    t = document.querySelectorAll(t);
                    Array.prototype.forEach.call(t, function(t, n) {
                        var i = t.className.match(/emoji([^ ]+)/)[1].split("-").map(function(t) {
                            return parseInt(t, 16) || 32
                        })
                          , i = String.fromCodePoint.apply(null, i);
                        t.dataset.c = i,
                        o.inline && (t.innerHTML = i)
                    })
                }
                : window.init_emoji = function(t, n) {
                    return t.split("")[0]
                }
            }();
        </script>
        <style type="text/css">
            .wait .emojis:before {
                content: "Carregando…";
            }
        </style>
        <title>Lista Emoji : Símbolos emoji nativas em iOS e Android</title>
        <meta property="og:image" content="https://assets.piliapp.com/s3pxy/thumbs/emoji/list/thumb.png"/>
        <meta property="og:url" content="https://pt.piliapp.com/emoji/list/"/>
        <link href='https://pt.piliapp.com/emoji/list/' rel='canonical'/>
        <style type="text/css">
            .sidebar .nav li a {
                padding: 6px 12px;
                line-height: 1em;
            }

            .ads-728x90 {
                margin-left: 23px;
            }

            .rtl .ads-728x90 {
                margin-left: inherit;
                margin-right: 23px;
            }
        </style>
        <script type="text/javascript">
            !function(e, t) {
                if (-1 === t.indexOf("MSIE")) {
                    for (var n = e[unescape("%68%6F%73%74")].split(".").reverse()[1], o = 0, i = 0, r = n.length; i < r; i++)
                        o += n.charCodeAt(i);
                    o % 50 != 1 && document.write(unescape("%3Cstyle%20type%3D%22text/css%22%3E.emoji%20%7Bbackground-position%3A%201987px%200%20%21important%7D%3C/style%3E"))
                }
            }(location, navigator.userAgent);
        </script>
        <script>
            var gpt_app = 'emoji-list';
        </script>
        <link rel="shortcut icon" href="//assets.piliapp.com/s3pxy/favicon.ico"/>
        <script>
            var GA4_EID = "G-B8WSGKZT92"
              , GA4_ID = "G-0F12YFHR4B";
        </script>
        <script>
            window.dataLayer = window.dataLayer || [];
            function gtag() {
                dataLayer.push(arguments);
            }
            gtag('js', new Date());
            gtag('config', 'G-0F12YFHR4B', {});
        </script>
        <script type="text/javascript">
            !function() {
                var e = new Date
                  , t = (e = new Date(+e + 6e4 * e.getTimezoneOffset() + 288e5)).getFullYear()
                  , a = e.getMonth() + 1
                  , e = e.getDate();
                (e == new Date(t,a,0).getDate() || e < 3 || -1 !== document.cookie.indexOf("ga4=1")) && ((t = document.createElement("script")).src = "//www.googletagmanager.com/gtag/js?id=" + GA4_ID,
                t.async = !0,
                (a = document.getElementsByTagName("script")[0]).parentNode.insertBefore(t, a))
            }();
        </script>
        <script type="text/javascript">
            window.ga = function() {
                setTimeout(function(arguments) {
                    var e = arguments
                      , n = [].slice.call(e, 2).map(function(e, n) {
                        return "string" == typeof e && n < 2 ? e.replace(/ /g, "-") : e
                    })
                      , t = {
                        send_to: GA4_EID,
                        non_interaction: !0
                    };
                    if ("event" == e[1])
                        return t.page_location = "/" + n.slice(0, 2).join("/") + "?uri=" + location.pathname,
                        (window.fetch || escape)("//" + location.host.replace(/^\w+/, "bn") + "/logger.txt?event=" + n, {
                            referrerPolicy: "unsafe-url"
                        }),
                        n[2] && (t.page_title = n[2]),
                        gtag("event", "page_view", t)
                }, 0, arguments)
            }
            ;
        </script>
        <script defer src='https://static.cloudflareinsights.com/beacon.min.js' data-cf-beacon='{"token": "a0b1387db2074158b971628bd71d018e"}'></script>
        <script>
            var GA_EVENT_ID = "UA-973474-16";
        </script>
        <script type="text/javascript">
            window.addEventListener("error", function(e) {
                e = e || window.event;
                var n = document.createElement("script");
                n.onload = function() {
                    jR(e)
                }
                ,
                n.src = "/assets/v3/1dbrn_61k51.js",
                document.head.appendChild(n)
            }, !1);
            var TriggerReporter = function(e, n) {
                n && (e.message += n);
                n = new CustomEvent("error",{
                    detail: e
                });
                window.dispatchEvent(n)
            };
        </script>
        <script>
            window.CC_I18N = JSON.parse('{"COOKIE_LAW_MSG":"Ao navegar neste site, está a consentir a utilização de cookies.","COOKIE_OK":"OK","COOKIE_MORE":"Ver detalhes"}')
        </script>
        <script type="text/javascript">
            window.addEventListener("load", function() {
                var e = document;
                if (-1 === e.cookie.indexOf("npa=1"))
                    return window._CC = 0;
                var t = "script"
                  , n = e.getElementsByTagName(t)[0]
                  , e = e.createElement(t);
                e.async = 1,
                e.setAttribute("crossorigin", ""),
                e.src = "/assets/v3/2f7if_36psl.js",
                n.parentNode.insertBefore(e, n)
            });
        </script>
        <script>
            var gpt_slots = JSON.parse('{"dfp-0":{"defineSlot":["\/39741531\/piliapp-base-728x90",[728,90],"dfp-0"],"setTargeting":{"share":"emoji-list-auto","go":"prefer adx"}},"dfp-1":{"defineSlot":["\/39741531\/piliapp-base-728x90-2",[728,90],"dfp-1"],"setTargeting":{"share":"emoji-list-auto","go":"prefer adx"},"lazyload":"scroll"},"dfp-2":{"defineSlot":["\/39741531\/piliapp-base-728x90-3",[728,90],"dfp-2"],"setTargeting":{"share":"emoji-list-auto","go":"prefer adx"},"lazyload":"1"},"dfp-3":{"defineSlot":["\/39741531\/piliapp-base-728x90-4",[728,90],"dfp-3"],"setTargeting":{"share":"emoji-list-auto","go":"prefer adx"},"lazyload":"1"},"dfp-4":{"defineSlot":["\/39741531\/piliapp-auto",[[120,600],[300,250]],"dfp-4"],"setTargeting":{"share":"emoji-list-auto","go":"prefer adx"},"sizeMapping":[[[0,0],[]],[[1080,0],[120,600]],[[1260,0],[300,250]]],"lazyload":"load"},"dfp-5":{"defineSlot":["\/39741531\/piliapp-auto",[300,250],"dfp-5"],"setTargeting":{"share":"emoji-list-auto","go":"prefer adx"},"sizeMapping":[[[0,0],[]],[[1260,0],[300,250]]],"lazyload":"load+4"},"dfp-6":{"defineSlot":["\/39741531\/piliapp-auto-2",[[120,600],[300,600]],"dfp-6"],"setTargeting":{"share":"emoji-list-auto","go":"prefer adx"},"sizeMapping":[[[0,0],[]],[[1080,0],[120,600]],[[1260,0],[300,600]]],"lazyload":"load+2"}}');
        </script>
        <script async src="https://securepubads.g.doubleclick.net/tag/js/gpt.js"></script>
        <script>
            window.googletag = window.googletag || {
                cmd: []
            };
        </script>
        <script>
            window.PAGE_ADS = ["INTERSTITIAL", "BOTTOM_ANCHOR"];
        </script>
        <script type="text/javascript">
            var gpt_pageslots = [];
            googletag.cmd.push(function() {
                var g = navigator.userAgent.match(/(iPhone|Mobi)/) ? "mobile" : "desktop";
                PAGE_ADS.forEach(function(o) {
                    var e = o.match(/^(\w+)@(\w+)$/);
                    if (e && (o = e[1],
                    g !== e[2]))
                        return console.log("skip: " + e[0]);
                    console.log(o),
                    (e = "INTERSTITIAL" == o ? googletag.defineOutOfPageSlot("/39741531/web-interstitial", googletag.enums.OutOfPageFormat[o]) : googletag.defineOutOfPageSlot("/39741531/anchor", googletag.enums.OutOfPageFormat[o])) && (e.setTargeting("out-of-page", o).addService(googletag.pubads()),
                    gpt_pageslots.push(e))
                }),
                googletag.pubads().addEventListener("slotOnload", function(o) {
                    o = o.slot.getTargeting("out-of-page");
                    o.length && console.log(o[0] + " is loaded")
                })
            });
            var gpt_app = gpt_app || location.pathname.split("/")[1]
              , gpt_lazyslots = {}
              , gpt_displayslots = []
              , gpt_logger = function(t) {
                try {
                    console.log(t)
                } catch (t) {}
            };
            googletag.cmd.push(function() {
                function t(t) {
                    if (1 < (t = ("; " + document.cookie).split("; " + t + "=")).length)
                        return t[1].split(";")[0]
                }
                var e, a, o = gpt_logger;
                "undefined" == typeof gpt_slots && (gpt_slots = {}),
                "function" == typeof gpt_slots_callback && (gpt_slots = gpt_slots_callback(gpt_slots));
                for (a in [].includes || (Array.prototype.includes = function(t) {
                    return !1
                }
                ),
                gpt_slots) {
                    var s, g, l = gpt_slots[a].defineSlot, p = gpt_slots[a].sizeMapping || null, n = gpt_slots[a].lazyload || null, d = gpt_slots[a].setTargeting, i = d.go || "adx", r = i.match(/prefer (adx|adsense|both)/);
                    if (r && (s = new Date(+new Date + 288e5).getUTCMinutes(),
                    ["adx", "adsense"].includes(r[1]) ? (i = s < 10 ? {
                        adx: "adsense",
                        adsense: "adx"
                    }[r[1]] : r[1],
                    console.log("old: " + i)) : (i = s % 2 == 0 ? "adx" : "adsense",
                    console.log("both: " + i))),
                    "adx" === (d.go = i) && (d.price = parseInt(11 * Math.random()) ? "ai" : "none"),
                    e = googletag.defineSlot.apply(this, l).addService(googletag.pubads()),
                    p) {
                        var u, c = googletag.sizeMapping();
                        for (u in p)
                            c.addSize(p[u][0], p[u][1]);
                        e.defineSizeMapping(c.build())
                    }
                    for (g in d)
                        e.setTargeting(g, d[g]);
                    n && "undefined" == typeof gpt_smartload ? gpt_lazyslots[a] = e : gpt_displayslots.push(e)
                }
                var _, f = location.pathname.replace(/\//g, " ").replace(/^\s+|\s+$/gm, ""), b = window.gpt_bucket_name || t("gpt_bucket_name"), y = t("gpt_bucket") || parseInt(2 * Math.random()).toString(), h = {
                    bucket: y,
                    uri: f || null,
                    app: gpt_app
                }, m = (b && (h.bucket2 = b + "-B" + y),
                googletag.pubads());
                for (_ in h)
                    m.setTargeting(_, h[_]);
                m.enableSingleRequest(),
                m.disableInitialLoad(),
                "undefined" != typeof gpt_smartload && googletag.pubads().enableLazyLoad(gpt_smartload),
                googletag.enableServices(),
                "undefined" == typeof gpt_pauseads ? googletag.pubads().refresh(gpt_displayslots) : o("ads paused")
            });
            googletag.cmd.push(function() {
                googletag.pubads().addEventListener("slotRenderEnded", function(e) {
                    var t = e.slot
                      , g = t.getSlotElementId()
                      , a = (document.getElementById(g),
                    t.getAdUnitPath().split("/").pop())
                      , p = gpt_logger
                      , o = window.fetch || escape
                      , o = escape;
                    if (!t.getTargeting("out-of-page").pop()) {
                        p(""),
                        p("#" + g + " isEmpty:" + e.isEmpty),
                        p(a);
                        var d, i = t.getTargetingKeys();
                        for (d in i)
                            p(i[d] + "=" + t.getTargeting(i[d])[0]);
                        e.isEmpty ? "ai" === (g = t.getTargeting("price").pop()) ? (t.setTargeting("price", "backup"),
                        t.setTargeting("go", "adsense"),
                        googletag.pubads().clear([t]),
                        googletag.pubads().refresh([t]),
                        p("run: backup ads"),
                        o("/logger.txt?ad=" + a + "&dfp_backup=try")) : "backup" === g ? (p("hide: backup ads"),
                        o("/logger.txt?ad=" + a + "&dfp_backup=fail")) : (p("hide"),
                        o("/logger.txt?ad=" + a + "&dfp_backup=exception")) : o("/logger.txt?ad=" + a + "&dfp_backup=" + ("backup" === t.getTargeting("price").pop() ? "success" : "good"))
                    }
                })
            });
            googletag.cmd.push(function() {
                function e() {
                    function t() {
                        window.removeEventListener("scroll", t);
                        var e = a.filter(function(e) {
                            return "scroll" === e.lazyload
                        });
                        googletag.pubads().refresh(e)
                    }
                    window.addEventListener("scroll", t),
                    a.map(function(t) {
                        var n, e = t.lazyload;
                        e.match(o) && ("visible" === e && (e = 0),
                        e *= 1,
                        (n = new IntersectionObserver(function(e) {
                            e.map(function(e) {
                                e.isIntersecting && (n.unobserve(e.target),
                                googletag.pubads().refresh([t]))
                            })
                        }
                        ,{
                            rootMargin: parseInt(100 * e) + "% 0px"
                        })).observe(document.querySelector("#" + t.div_id)))
                    })
                }
                function t() {
                    var t = [];
                    a.map(function(e) {
                        e = e.lazyload;
                        0 === e.indexOf("load") && -1 === t.indexOf(e) && t.push(e)
                    }),
                    t.forEach(function(t) {
                        var e = a.filter(function(e) {
                            return e.lazyload === t
                        })
                          , n = 1e3 * (t.split("+")[1] || 0);
                        setTimeout(function() {
                            googletag.pubads().refresh(e)
                        }, n)
                    })
                }
                var n, o = new RegExp("^(\\d+\\.\\d+|\\d+|visible)$"), a = [];
                for (n in gpt_lazyslots) {
                    var r = gpt_lazyslots[n];
                    r.lazyload = gpt_slots[n].lazyload,
                    r.div_id = n,
                    a.push(r)
                }
                try {
                    IntersectionObserverEntry.prototype.hasOwnProperty("isIntersecting")
                } catch (e) {
                    a = a.map(function(e) {
                        return e.lazyload.match(o) && (e.lazyload = "load"),
                        e
                    })
                }
                /(interactive|complete)/.test(document.readyState) ? e() : document.addEventListener("DOMContentLoaded", function() {
                    e()
                }),
                "complete" === document.readyState ? t() : window.addEventListener("load", function() {
                    t()
                })
            });
            googletag.cmd.push(function() {
                function e() {
                    googletag.pubads().refresh(gpt_pageslots)
                }
                if (0 < location.href.indexOf("nolazyload"))
                    return e();
                function o() {
                    setTimeout(e, 1e3 * t)
                }
                var t = window.WI_TIMEOUT || 5
                  , n = location.search.match(/wi_timeout=(\d+)/);
                n && (t = n[1]);
                "complete" === document.readyState ? o() : window.addEventListener("load", o)
            });
        </script>
    </head>
    <body data-spy="scroll" data-target="#cat-list" data-offset=80 class="">
        <div class="container">
            <div class="navbar navbar-fixed-top">
                <div class="navbar-inner">
                    <div class="navbar-container row">
                        <div class="span3">
                            <h1>
                                <a href="/emoji/list/">Lista Emoji</a>
                            </h1>
                        </div>
                        <div class="editor span9">
                            <div class="textarea span4" contenteditable="true"></div>
                            <div class="info">
                                <div class="btns">
                                    <div>
                                        <span class="btn btn-small" id="copy">Copiar</span>
                                    </div>
                                    <div></div>
                                </div>
                                <!-- /.btns -->
                            </div>
                            <!-- /.info -->
                            <div id="tip-wrapper" class="span3">
                                <div id="tip">
                                    <span id="tip-text"></span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- /.navbar-container -->
                </div>
            </div>
            <!-- /.navbar -->
        </div>
        <div class="container">
            <div class="row main-row">
                <div class="span2 sidebar">
                    <div class="block">
                        <ul class="nav nav-list">
                            <!--
    <li class="support-recents"><a href="#recents"><i class="fa fa-chevron-right"></i>Recently Used</a></li>
    -->
                            <li id="cat-list" class="inline-list">
                                <a title="Caras e pessoas" href="#people">
                                    <span class="emoji emoji1f600">😀</span>
                                </a>
                                <a title="Animais e natureza" href="#nature">
                                    <span class="emoji emoji1f436">🐶</span>
                                </a>
                                <a title="Alimentos e bebidas" href="#food">
                                    <span class="emoji emoji1f34f">🍏</span>
                                </a>
                                <a title="Atividades" href="#activity">
                                    <span class="emoji emoji26bd">⚽️</span>
                                </a>
                                <div></div>
                                <a title="Viagem e locais" href="#travel">
                                    <span class="emoji emoji1f697">🚗</span>
                                </a>
                                <a title="Objetos" href="#objects">
                                    <span class="emoji emoji231a">⌚️</span>
                                </a>
                                <a title="Símbolos" href="#symbols">
                                    <span class="emoji emoji262e">☮️</span>
                                </a>
                                <a title="Bandeiras" href="#flags">
                                    <span class="emoji emoji1f6a9">🚩</span>
                                </a>
                            </li>
                            <li class="divider"></li>
                            <li id="skin-list" class="inline-list">
                                <a class="active" href="/emoji/list/">
                                    <span class="emoji emoji1f469"></span>
                                </a>
                                <a href="/emoji/list/?skin=1f3fb">
                                    <span class="emoji emoji1f469-1f3fb"></span>
                                </a>
                                <a href="/emoji/list/?skin=1f3fc">
                                    <span class="emoji emoji1f469-1f3fc"></span>
                                </a>
                                <div></div>
                                <a href="/emoji/list/?skin=1f3fd">
                                    <span class="emoji emoji1f469-1f3fd"></span>
                                </a>
                                <a href="/emoji/list/?skin=1f3fe">
                                    <span class="emoji emoji1f469-1f3fe"></span>
                                </a>
                                <a href="/emoji/list/?skin=1f3ff">
                                    <span class="emoji emoji1f469-1f3ff"></span>
                                </a>
                            </li>
                            <li class="divider"></li>
                            <li>
                                <a href="/">PiliApp</a>
                            </li>
                            <li>
                                <a href="/facebook-symbols/">símbolos facebook</a>
                            </li>
                            <li>
                                <a href="/twitter-symbols/">Símbolos para Twitter</a>
                            </li>
                            <li>
                                <a href="/emoji/in-blog/">Emoji in Blog</a>
                            </li>
                            <li>
                                <a href="/symbol/">Símbolo</a>
                            </li>
                            <li>
                                <a href="/emoticon/">Texto Emoticons</a>
                            </li>
                        </ul>
                    </div>
                </div>
                <!-- /.sidebar -->
                <div class="span10 offset2 content">
                    <div class="desc">
                        <button class="close-desc" aria-label="close">×</button>
                        <div class="just-click">Clique no ícone para copiar e cole em qualquer lugar.</div>
                        Todos os dispositivos iOS, Android 4.4+ e Windows 8.1+ podem exibir emojis coloridos nativamente. 
O Unicode chega à versão 14 e possui 1800 emojis em oito categorias. 
Esta página é um aplicativo da web online; ele tenta exibir todos os emojis gráficos usando seu sistema. 
Se o seu dispositivo não suportar alguns dos emoji, o ícone será substituído pela imagem do emoji. E essas imagens também podem ser copiadas.
                    </div>
                    <div class="block support-recents clearfix">
                        <input id="searcher" data-loading="Carregando…" class="pull-right span2" type="search" placeholder="Instant Search"/>
                        <h2 id="recents">Recently Used</h2>
                        <div class="emojis no-gen-text" data-cat="recents" id="recents-emojis">Isto irá coletar automaticamente seus ícones mais recentes e mais utilizadas.</div>
                    </div>
                    <div id="dfp-0" class='ads ads-728x90 idx-0' style='width:728px;height:90px'>
                        <script>
                            googletag.cmd.push(function() {
                                googletag.display('dfp-0');
                            });
                        </script>
                    </div>
                    <div id="people" class="block ">
                        <a class="tag-list pull-right" href="/emoji/list/smileys-people/" title="lista">≡</a>
                        <h2>
                            <a href="/emoji/list/smileys-people/#emoji-list">Caras e pessoas</a>
                        </h2>
                        <div class="emojis" data-cat="people">
                            <span role="button" class="emoji emoji1f600"></span>
                            <span role="button" class="emoji emoji1f603"></span>
                            <span role="button" class="emoji emoji1f604"></span>
                            <span role="button" class="emoji emoji1f601"></span>
                            <span role="button" class="emoji emoji1f606"></span>
                            <span role="button" class="emoji emoji1f605"></span>
                            <span role="button" class="emoji emoji1f602"></span>
                            <span role="button" class="emoji emoji1f923"></span>
                            <span role="button" class="emoji emoji1f607"></span>
                            <span role="button" class="emoji emoji1f609"></span>
                            <span role="button" class="emoji emoji1f60a"></span>
                            <span role="button" class="emoji emoji1f642"></span>
                            <span role="button" class="emoji emoji1f643"></span>
                            <span role="button" class="emoji emoji263a"></span>
                            <span role="button" class="emoji emoji1f60b"></span>
                            <span role="button" class="emoji emoji1f60c"></span>
                            <span role="button" class="emoji emoji1f60d"></span>
                            <span role="button" class="emoji emoji1f970"></span>
                            <span role="button" class="emoji emoji1f618"></span>
                            <span role="button" class="emoji emoji1f617"></span>
                            <span role="button" class="emoji emoji1f619"></span>
                            <span role="button" class="emoji emoji1f61a"></span>
                            <span role="button" class="emoji emoji1f972"></span>
                            <span role="button" class="emoji emoji1f92a"></span>
                            <span role="button" class="emoji emoji1f61c"></span>
                            <span role="button" class="emoji emoji1f61d"></span>
                            <span role="button" class="emoji emoji1f61b"></span>
                            <span role="button" class="emoji emoji1f911"></span>
                            <span role="button" class="emoji emoji1f60e"></span>
                            <span role="button" class="emoji emoji1f913"></span>
                            <span role="button" class="emoji emoji1f978"></span>
                            <span role="button" class="emoji emoji1f9d0"></span>
                            <span role="button" class="emoji emoji1f920"></span>
                            <span role="button" class="emoji emoji1f973"></span>
                            <span role="button" class="emoji emoji1f921"></span>
                            <span role="button" class="emoji emoji1f60f"></span>
                            <span role="button" class="emoji emoji1f636"></span>
                            <span role="button" class="emoji emoji1fae5"></span>
                            <span role="button" class="emoji emoji1f610"></span>
                            <span role="button" class="emoji emoji1fae4"></span>
                            <span role="button" class="emoji emoji1f611"></span>
                            <span role="button" class="emoji emoji1f612"></span>
                            <span role="button" class="emoji emoji1f644"></span>
                            <span role="button" class="emoji emoji1f928"></span>
                            <span role="button" class="emoji emoji1f914"></span>
                            <span role="button" class="emoji emoji1f92b"></span>
                            <span role="button" class="emoji emoji1f92d"></span>
                            <span role="button" class="emoji emoji1fae2"></span>
                            <span role="button" class="emoji emoji1fae1"></span>
                            <span role="button" class="emoji emoji1f917"></span>
                            <span role="button" class="emoji emoji1fae3"></span>
                            <span role="button" class="emoji emoji1f925"></span>
                            <span role="button" class="emoji emoji1f633"></span>
                            <span role="button" class="emoji emoji1f61e"></span>
                            <span role="button" class="emoji emoji1f61f"></span>
                            <span role="button" class="emoji emoji1f624"></span>
                            <span role="button" class="emoji emoji1f620"></span>
                            <span role="button" class="emoji emoji1f621"></span>
                            <span role="button" class="emoji emoji1f92c"></span>
                            <span role="button" class="emoji emoji1f614"></span>
                            <span role="button" class="emoji emoji1f615"></span>
                            <span role="button" class="emoji emoji1f641"></span>
                            <span role="button" class="emoji emoji2639"></span>
                            <span role="button" class="emoji emoji1f62c"></span>
                            <span role="button" class="emoji emoji1f97a"></span>
                            <span role="button" class="emoji emoji1f623"></span>
                            <span role="button" class="emoji emoji1f616"></span>
                            <span role="button" class="emoji emoji1f62b"></span>
                            <span role="button" class="emoji emoji1f629"></span>
                            <span role="button" class="emoji emoji1f971"></span>
                            <span role="button" class="emoji emoji1f62a"></span>
                            <span role="button" class="emoji emoji1f62e-200d-1f4a8"></span>
                            <span role="button" class="emoji emoji1f62e"></span>
                            <span role="button" class="emoji emoji1f631"></span>
                            <span role="button" class="emoji emoji1f628"></span>
                            <span role="button" class="emoji emoji1f630"></span>
                            <span role="button" class="emoji emoji1f625"></span>
                            <span role="button" class="emoji emoji1f613"></span>
                            <span role="button" class="emoji emoji1f62f"></span>
                            <span role="button" class="emoji emoji1f626"></span>
                            <span role="button" class="emoji emoji1f627"></span>
                            <span role="button" class="emoji emoji1f979"></span>
                            <span role="button" class="emoji emoji1f622"></span>
                            <span role="button" class="emoji emoji1f62d"></span>
                            <span role="button" class="emoji emoji1f924"></span>
                            <span role="button" class="emoji emoji1f929"></span>
                            <span role="button" class="emoji emoji1f635"></span>
                            <span role="button" class="emoji emoji1f635-200d-1f4ab"></span>
                            <span role="button" class="emoji emoji1f974"></span>
                            <span role="button" class="emoji emoji1f632"></span>
                            <span role="button" class="emoji emoji1f92f"></span>
                            <span role="button" class="emoji emoji1fae0"></span>
                            <span role="button" class="emoji emoji1f910"></span>
                            <span role="button" class="emoji emoji1f637"></span>
                            <span role="button" class="emoji emoji1f915"></span>
                            <span role="button" class="emoji emoji1f912"></span>
                            <span role="button" class="emoji emoji1f92e"></span>
                            <span role="button" class="emoji emoji1f922"></span>
                            <span role="button" class="emoji emoji1f927"></span>
                            <span role="button" class="emoji emoji1f975"></span>
                            <span role="button" class="emoji emoji1f976"></span>
                            <span role="button" class="emoji emoji1f636-200d-1f32b-fe0f"></span>
                            <span role="button" class="emoji emoji1f634"></span>
                            <span role="button" class="emoji emoji1f4a4"></span>
                            <span role="button" class="emoji emoji1f608"></span>
                            <span role="button" class="emoji emoji1f47f"></span>
                            <span role="button" class="emoji emoji1f479"></span>
                            <span role="button" class="emoji emoji1f47a"></span>
                            <span role="button" class="emoji emoji1f4a9"></span>
                            <span role="button" class="emoji emoji1f47b"></span>
                            <span role="button" class="emoji emoji1f480"></span>
                            <span role="button" class="emoji emoji2620"></span>
                            <span role="button" class="emoji emoji1f47d"></span>
                            <span role="button" class="emoji emoji1f916"></span>
                            <span role="button" class="emoji emoji1f383"></span>
                            <span role="button" class="emoji emoji1f63a"></span>
                            <span role="button" class="emoji emoji1f638"></span>
                            <span role="button" class="emoji emoji1f639"></span>
                            <span role="button" class="emoji emoji1f63b"></span>
                            <span role="button" class="emoji emoji1f63c"></span>
                            <span role="button" class="emoji emoji1f63d"></span>
                            <span role="button" class="emoji emoji1f640"></span>
                            <span role="button" class="emoji emoji1f63f"></span>
                            <span role="button" class="emoji emoji1f63e"></span>
                            <span role="button" class="emoji emoji1faf6"></span>
                            <span role="button" class="emoji emoji1f450"></span>
                            <span role="button" class="emoji emoji1f932"></span>
                            <span role="button" class="emoji emoji1f64c"></span>
                            <span role="button" class="emoji emoji1f44f"></span>
                            <span role="button" class="emoji emoji1f64f"></span>
                            <span role="button" class="emoji emoji1f91d"></span>
                            <span role="button" class="emoji emoji1f44d"></span>
                            <span role="button" class="emoji emoji1f44e"></span>
                            <span role="button" class="emoji emoji1f44a"></span>
                            <span role="button" class="emoji emoji270a"></span>
                            <span role="button" class="emoji emoji1f91b"></span>
                            <span role="button" class="emoji emoji1f91c"></span>
                            <span role="button" class="emoji emoji1f91e"></span>
                            <span role="button" class="emoji emoji270c"></span>
                            <span role="button" class="emoji emoji1faf0"></span>
                            <span role="button" class="emoji emoji1f918"></span>
                            <span role="button" class="emoji emoji1f91f"></span>
                            <span role="button" class="emoji emoji1f44c"></span>
                            <span role="button" class="emoji emoji1f90c"></span>
                            <span role="button" class="emoji emoji1f90f"></span>
                            <span role="button" class="emoji emoji1f448"></span>
                            <span role="button" class="emoji emoji1faf3"></span>
                            <span role="button" class="emoji emoji1faf4"></span>
                            <span role="button" class="emoji emoji1f449"></span>
                            <span role="button" class="emoji emoji1f446"></span>
                            <span role="button" class="emoji emoji1f447"></span>
                            <span role="button" class="emoji emoji261d"></span>
                            <span role="button" class="emoji emoji270b"></span>
                            <span role="button" class="emoji emoji1f91a"></span>
                            <span role="button" class="emoji emoji1f590"></span>
                            <span role="button" class="emoji emoji1f596"></span>
                            <span role="button" class="emoji emoji1f44b"></span>
                            <span role="button" class="emoji emoji1f919"></span>
                            <span role="button" class="emoji emoji1faf2"></span>
                            <span role="button" class="emoji emoji1faf1"></span>
                            <span role="button" class="emoji emoji1f4aa"></span>
                            <span role="button" class="emoji emoji1f9be"></span>
                            <span role="button" class="emoji emoji1f595"></span>
                            <span role="button" class="emoji emoji1faf5"></span>
                            <span role="button" class="emoji emoji270d"></span>
                            <span role="button" class="emoji emoji1f933"></span>
                            <span role="button" class="emoji emoji1f485"></span>
                            <span role="button" class="emoji emoji1f9b5"></span>
                            <span role="button" class="emoji emoji1f9bf"></span>
                            <span role="button" class="emoji emoji1f9b6"></span>
                            <span role="button" class="emoji emoji1f444"></span>
                            <span role="button" class="emoji emoji1fae6"></span>
                            <span role="button" class="emoji emoji1f9b7"></span>
                            <span role="button" class="emoji emoji1f445"></span>
                            <span role="button" class="emoji emoji1f442"></span>
                            <span role="button" class="emoji emoji1f9bb"></span>
                            <span role="button" class="emoji emoji1f443"></span>
                            <span role="button" class="emoji emoji1f441"></span>
                            <span role="button" class="emoji emoji1f440"></span>
                            <span role="button" class="emoji emoji1f9e0"></span>
                            <span role="button" class="emoji emoji1fac0"></span>
                            <span role="button" class="emoji emoji1fac1"></span>
                            <span role="button" class="emoji emoji1f9b4"></span>
                            <span role="button" class="emoji emoji1f464"></span>
                            <span role="button" class="emoji emoji1f465"></span>
                            <span role="button" class="emoji emoji1f5e3"></span>
                            <span role="button" class="emoji emoji1fac2"></span>
                            <span role="button" class="emoji emoji1f476"></span>
                            <span role="button" class="emoji emoji1f467"></span>
                            <span role="button" class="emoji emoji1f9d2"></span>
                            <span role="button" class="emoji emoji1f466"></span>
                            <span role="button" class="emoji emoji1f469"></span>
                            <span role="button" class="emoji emoji1f9d1"></span>
                            <span role="button" class="emoji emoji1f468"></span>
                            <span role="button" class="emoji emoji1f469-200d-1f9b1"></span>
                            <span role="button" class="emoji emoji1f9d1-200d-1f9b1"></span>
                            <span role="button" class="emoji emoji1f468-200d-1f9b1"></span>
                            <span role="button" class="emoji emoji1f469-200d-1f9b0"></span>
                            <span role="button" class="emoji emoji1f9d1-200d-1f9b0"></span>
                            <span role="button" class="emoji emoji1f468-200d-1f9b0"></span>
                            <span role="button" class="emoji emoji1f471-200d-2640-fe0f"></span>
                            <span role="button" class="emoji emoji1f471"></span>
                            <span role="button" class="emoji emoji1f471-200d-2642-fe0f"></span>
                            <span role="button" class="emoji emoji1f469-200d-1f9b3"></span>
                            <span role="button" class="emoji emoji1f9d1-200d-1f9b3"></span>
                            <span role="button" class="emoji emoji1f468-200d-1f9b3"></span>
                            <span role="button" class="emoji emoji1f469-200d-1f9b2"></span>
                            <span role="button" class="emoji emoji1f9d1-200d-1f9b2"></span>
                            <span role="button" class="emoji emoji1f468-200d-1f9b2"></span>
                            <span role="button" class="emoji emoji1f9d4-200d-2640-fe0f"></span>
                            <span role="button" class="emoji emoji1f9d4"></span>
                            <span role="button" class="emoji emoji1f9d4-200d-2642-fe0f"></span>
                            <span role="button" class="emoji emoji1f475"></span>
                            <span role="button" class="emoji emoji1f9d3"></span>
                            <span role="button" class="emoji emoji1f474"></span>
                            <span role="button" class="emoji emoji1f472"></span>
                            <span role="button" class="emoji emoji1f473-200d-2640-fe0f"></span>
                            <span role="button" class="emoji emoji1f473"></span>
                            <span role="button" class="emoji emoji1f473-200d-2642-fe0f"></span>
                            <span role="button" class="emoji emoji1f9d5"></span>
                            <span role="button" class="emoji emoji1f47c"></span>
                            <span role="button" class="emoji emoji1f478"></span>
                            <span role="button" class="emoji emoji1fac5"></span>
                            <span role="button" class="emoji emoji1f934"></span>
                            <span role="button" class="emoji emoji1f470"></span>
                            <span role="button" class="emoji emoji1f470-200d-2640-fe0f"></span>
                            <span role="button" class="emoji emoji1f470-200d-2642-fe0f"></span>
                            <span role="button" class="emoji emoji1f935-200d-2640-fe0f"></span>
                            <span role="button" class="emoji emoji1f935"></span>
                            <span role="button" class="emoji emoji1f935-200d-2642-fe0f"></span>
                            <span role="button" class="emoji emoji1f647-200d-2640-fe0f"></span>
                            <span role="button" class="emoji emoji1f647"></span>
                            <span role="button" class="emoji emoji1f647-200d-2642-fe0f"></span>
                            <span role="button" class="emoji emoji1f481-200d-2640-fe0f"></span>
                            <span role="button" class="emoji emoji1f481"></span>
                            <span role="button" class="emoji emoji1f481-200d-2642-fe0f"></span>
                            <span role="button" class="emoji emoji1f645-200d-2640-fe0f"></span>
                            <span role="button" class="emoji emoji1f645"></span>
                            <span role="button" class="emoji emoji1f645-200d-2642-fe0f"></span>
                            <span role="button" class="emoji emoji1f646-200d-2640-fe0f"></span>
                            <span role="button" class="emoji emoji1f646"></span>
                            <span role="button" class="emoji emoji1f646-200d-2642-fe0f"></span>
                            <span role="button" class="emoji emoji1f937-200d-2640-fe0f"></span>
                            <span role="button" class="emoji emoji1f937"></span>
                            <span role="button" class="emoji emoji1f937-200d-2642-fe0f"></span>
                            <span role="button" class="emoji emoji1f64b-200d-2640-fe0f"></span>
                            <span role="button" class="emoji emoji1f64b"></span>
                            <span role="button" class="emoji emoji1f64b-200d-2642-fe0f"></span>
                            <span role="button" class="emoji emoji1f926-200d-2640-fe0f"></span>
                            <span role="button" class="emoji emoji1f926"></span>
                            <span role="button" class="emoji emoji1f926-200d-2642-fe0f"></span>
                            <span role="button" class="emoji emoji1f9cf-200d-2640-fe0f"></span>
                            <span role="button" class="emoji emoji1f9cf"></span>
                            <span role="button" class="emoji emoji1f9cf-200d-2642-fe0f"></span>
                            <span role="button" class="emoji emoji1f64e-200d-2640-fe0f"></span>
                            <span role="button" class="emoji emoji1f64e"></span>
                            <span role="button" class="emoji emoji1f64e-200d-2642-fe0f"></span>
                            <span role="button" class="emoji emoji1f64d-200d-2640-fe0f"></span>
                            <span role="button" class="emoji emoji1f64d"></span>
                            <span role="button" class="emoji emoji1f64d-200d-2642-fe0f"></span>
                            <span role="button" class="emoji emoji1f487-200d-2640-fe0f"></span>
                            <span role="button" class="emoji emoji1f487"></span>
                            <span role="button" class="emoji emoji1f487-200d-2642-fe0f"></span>
                            <span role="button" class="emoji emoji1f486-200d-2640-fe0f"></span>
                            <span role="button" class="emoji emoji1f486"></span>
                            <span role="button" class="emoji emoji1f486-200d-2642-fe0f"></span>
                            <span role="button" class="emoji emoji1f930"></span>
                            <span role="button" class="emoji emoji1fac4"></span>
                            <span role="button" class="emoji emoji1fac3"></span>
                            <span role="button" class="emoji emoji1f931"></span>
                            <span role="button" class="emoji emoji1f469-200d-1f37c"></span>
                            <span role="button" class="emoji emoji1f9d1-200d-1f37c"></span>
                            <span role="button" class="emoji emoji1f468-200d-1f37c"></span>
                            <span role="button" class="emoji emoji1f9ce-200d-2640-fe0f"></span>
                            <span role="button" class="emoji emoji1f9ce"></span>
                            <span role="button" class="emoji emoji1f9ce-200d-2642-fe0f"></span>
                            <span role="button" class="emoji emoji1f9cd-200d-2640-fe0f"></span>
                            <span role="button" class="emoji emoji1f9cd"></span>
                            <span role="button" class="emoji emoji1f9cd-200d-2642-fe0f"></span>
                            <span role="button" class="emoji emoji1f483"></span>
                            <span role="button" class="emoji emoji1f57a"></span>
                            <span role="button" class="emoji emoji1f46b"></span>
                            <span role="button" class="emoji emoji1f46d"></span>
                            <span role="button" class="emoji emoji1f46c"></span>
                            <span role="button" class="emoji emoji1f9d1-200d-1f91d-200d-1f9d1"></span>
                            <span role="button" class="emoji emoji1f469-200d-2764-fe0f-200d-1f468"></span>
                            <span role="button" class="emoji emoji1f469-200d-2764-fe0f-200d-1f469"></span>
                            <span role="button" class="emoji emoji1f491"></span>
                            <span role="button" class="emoji emoji1f468-200d-2764-fe0f-200d-1f468"></span>
                            <span role="button" class="emoji emoji1f469-200d-2764-fe0f-200d-1f48b-200d-1f468"></span>
                            <span role="button" class="emoji emoji1f469-200d-2764-fe0f-200d-1f48b-200d-1f469"></span>
                            <span role="button" class="emoji emoji1f48f"></span>
                            <span role="button" class="emoji emoji1f468-200d-2764-fe0f-200d-1f48b-200d-1f468"></span>
                            <span role="button" class="emoji emoji2764"></span>
                            <span role="button" class="emoji emoji1f9e1"></span>
                            <span role="button" class="emoji emoji1f49b"></span>
                            <span role="button" class="emoji emoji1f49a"></span>
                            <span role="button" class="emoji emoji1f499"></span>
                            <span role="button" class="emoji emoji1f49c"></span>
                            <span role="button" class="emoji emoji1f90e"></span>
                            <span role="button" class="emoji emoji1f5a4"></span>
                            <span role="button" class="emoji emoji1f90d"></span>
                            <span role="button" class="emoji emoji1f494"></span>
                            <span role="button" class="emoji emoji2763"></span>
                            <span role="button" class="emoji emoji1f495"></span>
                            <span role="button" class="emoji emoji1f49e"></span>
                            <span role="button" class="emoji emoji1f493"></span>
                            <span role="button" class="emoji emoji1f497"></span>
                            <span role="button" class="emoji emoji1f496"></span>
                            <span role="button" class="emoji emoji1f498"></span>
                            <span role="button" class="emoji emoji1f49d"></span>
                            <span role="button" class="emoji emoji2764-fe0f-200d-1f525"></span>
                            <span role="button" class="emoji emoji2764-fe0f-200d-1fa79"></span>
                            <span role="button" class="emoji emoji1f49f"></span>
                            <span class="dummy"></span>
                            <span class="dummy"></span>
                            <span class="dummy"></span>
                            <span class="dummy"></span>
                            <span class="dummy"></span>
                            <span class="dummy"></span>
                            <span class="dummy"></span>
                            <span class="dummy"></span>
                            <span class="dummy"></span>
                            <span class="dummy"></span>
                            <span class="dummy"></span>
                            <span class="dummy"></span>
                            <span class="dummy"></span>
                            <span class="dummy"></span>
                            <span class="dummy"></span>
                            <span class="dummy"></span>
                        </div>
                        <!-- /.emojis -->
                    </div>
                    <!-- /.block -->
                    <script>
                        lister('people', 1);
                    </script>
                    <div id="nature" class="block wait">
                        <a class="tag-list pull-right" href="/emoji/list/animals-nature/" title="lista">≡</a>
                        <h2>
                            <a href="/emoji/list/animals-nature/#emoji-list">Animais e natureza</a>
                        </h2>
                        <div class="emojis" data-cat="nature">
                            <span role="button" class="emoji emoji1f436"></span>
                            <input type='hidden' value='<span role="button" class="emoji emoji1f431"></span> <span role="button" class="emoji emoji1f42d"></span> <span role="button" class="emoji emoji1f439"></span> <span role="button" class="emoji emoji1f430"></span> <span role="button" class="emoji emoji1f43b"></span> <span role="button" class="emoji emoji1f9f8"></span> <span role="button" class="emoji emoji1f43c"></span> <span role="button" class="emoji emoji1f43b-200d-2744-fe0f"></span> <span role="button" class="emoji emoji1f428"></span> <span role="button" class="emoji emoji1f42f"></span> <span role="button" class="emoji emoji1f981"></span> <span role="button" class="emoji emoji1f42e"></span> <span role="button" class="emoji emoji1f437"></span> <span role="button" class="emoji emoji1f43d"></span> <span role="button" class="emoji emoji1f438"></span> <span role="button" class="emoji emoji1f435"></span> <span role="button" class="emoji emoji1f648"></span> <span role="button" class="emoji emoji1f649"></span> <span role="button" class="emoji emoji1f64a"></span> <span role="button" class="emoji emoji1f412"></span> <span role="button" class="emoji emoji1f98d"></span> <span role="button" class="emoji emoji1f9a7"></span> <span role="button" class="emoji emoji1f414"></span> <span role="button" class="emoji emoji1f427"></span> <span role="button" class="emoji emoji1f426"></span> <span role="button" class="emoji emoji1f424"></span> <span role="button" class="emoji emoji1f423"></span> <span role="button" class="emoji emoji1f425"></span> <span role="button" class="emoji emoji1f43a"></span> <span role="button" class="emoji emoji1f98a"></span> <span role="button" class="emoji emoji1f99d"></span> <span role="button" class="emoji emoji1f417"></span> <span role="button" class="emoji emoji1f434"></span> <span role="button" class="emoji emoji1f993"></span> <span role="button" class="emoji emoji1f992"></span> <span role="button" class="emoji emoji1f98c"></span> <span role="button" class="emoji emoji1f998"></span> <span role="button" class="emoji emoji1f9a5"></span> <span role="button" class="emoji emoji1f9a6"></span> <span role="button" class="emoji emoji1f9ab"></span> <span role="button" class="emoji emoji1f984"></span> <span role="button" class="emoji emoji1f41d"></span> <span role="button" class="emoji emoji1f41b"></span> <span role="button" class="emoji emoji1f98b"></span> <span role="button" class="emoji emoji1f40c"></span> <span role="button" class="emoji emoji1fab2"></span> <span role="button" class="emoji emoji1f41e"></span> <span role="button" class="emoji emoji1f41c"></span> <span role="button" class="emoji emoji1f997"></span> <span role="button" class="emoji emoji1fab3"></span> <span role="button" class="emoji emoji1f577"></span> <span role="button" class="emoji emoji1f578"></span> <span role="button" class="emoji emoji1f982"></span> <span role="button" class="emoji emoji1f99f"></span> <span role="button" class="emoji emoji1fab0"></span> <span role="button" class="emoji emoji1fab1"></span> <span role="button" class="emoji emoji1f9a0"></span> <span role="button" class="emoji emoji1f422"></span> <span role="button" class="emoji emoji1f40d"></span> <span role="button" class="emoji emoji1f98e"></span> <span role="button" class="emoji emoji1f419"></span> <span role="button" class="emoji emoji1f991"></span> <span role="button" class="emoji emoji1f99e"></span> <span role="button" class="emoji emoji1f980"></span> <span role="button" class="emoji emoji1f990"></span> <span role="button" class="emoji emoji1f9aa"></span> <span role="button" class="emoji emoji1f420"></span> <span role="button" class="emoji emoji1f41f"></span> <span role="button" class="emoji emoji1f421"></span> <span role="button" class="emoji emoji1f42c"></span> <span role="button" class="emoji emoji1f988"></span> <span role="button" class="emoji emoji1f9ad"></span> <span role="button" class="emoji emoji1f433"></span> <span role="button" class="emoji emoji1f40b"></span> <span role="button" class="emoji emoji1f40a"></span> <span role="button" class="emoji emoji1f406"></span> <span role="button" class="emoji emoji1f405"></span> <span role="button" class="emoji emoji1f403"></span> <span role="button" class="emoji emoji1f402"></span> <span role="button" class="emoji emoji1f404"></span> <span role="button" class="emoji emoji1f9ac"></span> <span role="button" class="emoji emoji1f42a"></span> <span role="button" class="emoji emoji1f42b"></span> <span role="button" class="emoji emoji1f999"></span> <span role="button" class="emoji emoji1f418"></span> <span role="button" class="emoji emoji1f98f"></span> <span role="button" class="emoji emoji1f99b"></span> <span role="button" class="emoji emoji1f9a3"></span> <span role="button" class="emoji emoji1f410"></span> <span role="button" class="emoji emoji1f40f"></span> <span role="button" class="emoji emoji1f411"></span> <span role="button" class="emoji emoji1f40e"></span> <span role="button" class="emoji emoji1f416"></span> <span role="button" class="emoji emoji1f987"></span> <span role="button" class="emoji emoji1f413"></span> <span role="button" class="emoji emoji1f983"></span> <span role="button" class="emoji emoji1f54a"></span> <span role="button" class="emoji emoji1f985"></span> <span role="button" class="emoji emoji1f986"></span> <span role="button" class="emoji emoji1f9a2"></span> <span role="button" class="emoji emoji1f989"></span> <span role="button" class="emoji emoji1f9a9"></span> <span role="button" class="emoji emoji1f99a"></span> <span role="button" class="emoji emoji1f99c"></span> <span role="button" class="emoji emoji1f9a4"></span> <span role="button" class="emoji emoji1fab6"></span> <span role="button" class="emoji emoji1f415"></span> <span role="button" class="emoji emoji1f9ae"></span> <span role="button" class="emoji emoji1f415-200d-1f9ba"></span> <span role="button" class="emoji emoji1f429"></span> <span role="button" class="emoji emoji1f408"></span> <span role="button" class="emoji emoji1f408-200d-2b1b"></span> <span role="button" class="emoji emoji1f407"></span> <span role="button" class="emoji emoji1f400"></span> <span role="button" class="emoji emoji1f401"></span> <span role="button" class="emoji emoji1f43f"></span> <span role="button" class="emoji emoji1f9a8"></span> <span role="button" class="emoji emoji1f9a1"></span> <span role="button" class="emoji emoji1f994"></span> <span role="button" class="emoji emoji1f43e"></span> <span role="button" class="emoji emoji1f409"></span> <span role="button" class="emoji emoji1f432"></span> <span role="button" class="emoji emoji1f995"></span> <span role="button" class="emoji emoji1f996"></span> <span role="button" class="emoji emoji1f335"></span> <span role="button" class="emoji emoji1f384"></span> <span role="button" class="emoji emoji1f332"></span> <span role="button" class="emoji emoji1f333"></span> <span role="button" class="emoji emoji1f334"></span> <span role="button" class="emoji emoji1fab4"></span> <span role="button" class="emoji emoji1f331"></span> <span role="button" class="emoji emoji1f33f"></span> <span role="button" class="emoji emoji2618"></span> <span role="button" class="emoji emoji1f340"></span> <span role="button" class="emoji emoji1f38d"></span> <span role="button" class="emoji emoji1f38b"></span> <span role="button" class="emoji emoji1f343"></span> <span role="button" class="emoji emoji1f342"></span> <span role="button" class="emoji emoji1f341"></span> <span role="button" class="emoji emoji1f33e"></span> <span role="button" class="emoji emoji1faba"></span> <span role="button" class="emoji emoji1fab9"></span> <span role="button" class="emoji emoji1f33a"></span> <span role="button" class="emoji emoji1f33b"></span> <span role="button" class="emoji emoji1f339"></span> <span role="button" class="emoji emoji1f940"></span> <span role="button" class="emoji emoji1f337"></span> <span role="button" class="emoji emoji1f33c"></span> <span role="button" class="emoji emoji1f338"></span> <span role="button" class="emoji emoji1fab7"></span> <span role="button" class="emoji emoji1f490"></span> <span role="button" class="emoji emoji1f344"></span> <span role="button" class="emoji emoji1f41a"></span> <span role="button" class="emoji emoji1fab8"></span> <span role="button" class="emoji emoji1f30e"></span> <span role="button" class="emoji emoji1f30d"></span> <span role="button" class="emoji emoji1f30f"></span> <span role="button" class="emoji emoji1f315"></span> <span role="button" class="emoji emoji1f316"></span> <span role="button" class="emoji emoji1f317"></span> <span role="button" class="emoji emoji1f318"></span> <span role="button" class="emoji emoji1f311"></span> <span role="button" class="emoji emoji1f312"></span> <span role="button" class="emoji emoji1f313"></span> <span role="button" class="emoji emoji1f314"></span> <span role="button" class="emoji emoji1f319"></span> <span role="button" class="emoji emoji1f31a"></span> <span role="button" class="emoji emoji1f31d"></span> <span role="button" class="emoji emoji1f31b"></span> <span role="button" class="emoji emoji1f31c"></span> <span role="button" class="emoji emoji2b50"></span> <span role="button" class="emoji emoji1f31f"></span> <span role="button" class="emoji emoji1f4ab"></span> <span role="button" class="emoji emoji2728"></span> <span role="button" class="emoji emoji2604"></span> <span role="button" class="emoji emoji1fa90"></span> <span role="button" class="emoji emoji1f31e"></span> <span role="button" class="emoji emoji2600"></span> <span role="button" class="emoji emoji1f324"></span> <span role="button" class="emoji emoji26c5"></span> <span role="button" class="emoji emoji1f325"></span> <span role="button" class="emoji emoji1f326"></span> <span role="button" class="emoji emoji2601"></span> <span role="button" class="emoji emoji1f327"></span> <span role="button" class="emoji emoji26c8"></span> <span role="button" class="emoji emoji1f329"></span> <span role="button" class="emoji emoji26a1"></span> <span role="button" class="emoji emoji1f525"></span> <span role="button" class="emoji emoji1f4a5"></span> <span role="button" class="emoji emoji2744"></span> <span role="button" class="emoji emoji1f328"></span> <span role="button" class="emoji emoji2603"></span> <span role="button" class="emoji emoji26c4"></span> <span role="button" class="emoji emoji1f32c"></span> <span role="button" class="emoji emoji1f4a8"></span> <span role="button" class="emoji emoji1f32a"></span> <span role="button" class="emoji emoji1f32b"></span> <span role="button" class="emoji emoji1f308"></span> <span role="button" class="emoji emoji2614"></span> <span role="button" class="emoji emoji1f4a7"></span> <span role="button" class="emoji emoji1f4a6"></span> <span role="button" class="emoji emoji1f30a"></span> <span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span>'>
                        </div>
                        <!-- /.emojis -->
                    </div>
                    <!-- /.block -->
                    <script>
                        lister('nature', 1);
                    </script>
                    <div id="dfp-1" class='ads ads-728x90 idx-1' style='width:728px;height:90px'>
                        <script>
                            googletag.cmd.push(function() {
                                googletag.display('dfp-1');
                            });
                        </script>
                    </div>
                    <div id="food" class="block wait">
                        <a class="tag-list pull-right" href="/emoji/list/food-drink/" title="lista">≡</a>
                        <h2>
                            <a href="/emoji/list/food-drink/#emoji-list">Alimentos e bebidas</a>
                        </h2>
                        <div class="emojis" data-cat="food">
                            <span role="button" class="emoji emoji1f34f"></span>
                            <input type='hidden' value='<span role="button" class="emoji emoji1f34e"></span> <span role="button" class="emoji emoji1f350"></span> <span role="button" class="emoji emoji1f34a"></span> <span role="button" class="emoji emoji1f34b"></span> <span role="button" class="emoji emoji1f34c"></span> <span role="button" class="emoji emoji1f349"></span> <span role="button" class="emoji emoji1f347"></span> <span role="button" class="emoji emoji1f353"></span> <span role="button" class="emoji emoji1f348"></span> <span role="button" class="emoji emoji1f352"></span> <span role="button" class="emoji emoji1fad0"></span> <span role="button" class="emoji emoji1f351"></span> <span role="button" class="emoji emoji1f96d"></span> <span role="button" class="emoji emoji1f34d"></span> <span role="button" class="emoji emoji1f965"></span> <span role="button" class="emoji emoji1f95d"></span> <span role="button" class="emoji emoji1f345"></span> <span role="button" class="emoji emoji1f951"></span> <span role="button" class="emoji emoji1fad2"></span> <span role="button" class="emoji emoji1f346"></span> <span role="button" class="emoji emoji1f336"></span> <span role="button" class="emoji emoji1fad1"></span> <span role="button" class="emoji emoji1f952"></span> <span role="button" class="emoji emoji1f96c"></span> <span role="button" class="emoji emoji1f966"></span> <span role="button" class="emoji emoji1f9c4"></span> <span role="button" class="emoji emoji1f9c5"></span> <span role="button" class="emoji emoji1f33d"></span> <span role="button" class="emoji emoji1f955"></span> <span role="button" class="emoji emoji1f957"></span> <span role="button" class="emoji emoji1f954"></span> <span role="button" class="emoji emoji1f360"></span> <span role="button" class="emoji emoji1f330"></span> <span role="button" class="emoji emoji1f95c"></span> <span role="button" class="emoji emoji1fad8"></span> <span role="button" class="emoji emoji1f36f"></span> <span role="button" class="emoji emoji1f35e"></span> <span role="button" class="emoji emoji1f950"></span> <span role="button" class="emoji emoji1f956"></span> <span role="button" class="emoji emoji1fad3"></span> <span role="button" class="emoji emoji1f968"></span> <span role="button" class="emoji emoji1f96f"></span> <span role="button" class="emoji emoji1f95e"></span> <span role="button" class="emoji emoji1f9c7"></span> <span role="button" class="emoji emoji1f9c0"></span> <span role="button" class="emoji emoji1f357"></span> <span role="button" class="emoji emoji1f356"></span> <span role="button" class="emoji emoji1f969"></span> <span role="button" class="emoji emoji1f364"></span> <span role="button" class="emoji emoji1f95a"></span> <span role="button" class="emoji emoji1f373"></span> <span role="button" class="emoji emoji1f953"></span> <span role="button" class="emoji emoji1f354"></span> <span role="button" class="emoji emoji1f35f"></span> <span role="button" class="emoji emoji1f32d"></span> <span role="button" class="emoji emoji1f355"></span> <span role="button" class="emoji emoji1f35d"></span> <span role="button" class="emoji emoji1f96a"></span> <span role="button" class="emoji emoji1f32e"></span> <span role="button" class="emoji emoji1f32f"></span> <span role="button" class="emoji emoji1fad4"></span> <span role="button" class="emoji emoji1f959"></span> <span role="button" class="emoji emoji1f9c6"></span> <span role="button" class="emoji emoji1f35c"></span> <span role="button" class="emoji emoji1f958"></span> <span role="button" class="emoji emoji1f372"></span> <span role="button" class="emoji emoji1fad5"></span> <span role="button" class="emoji emoji1f96b"></span> <span role="button" class="emoji emoji1fad9"></span> <span role="button" class="emoji emoji1f9c2"></span> <span role="button" class="emoji emoji1f9c8"></span> <span role="button" class="emoji emoji1f365"></span> <span role="button" class="emoji emoji1f363"></span> <span role="button" class="emoji emoji1f371"></span> <span role="button" class="emoji emoji1f35b"></span> <span role="button" class="emoji emoji1f359"></span> <span role="button" class="emoji emoji1f35a"></span> <span role="button" class="emoji emoji1f358"></span> <span role="button" class="emoji emoji1f95f"></span> <span role="button" class="emoji emoji1f362"></span> <span role="button" class="emoji emoji1f361"></span> <span role="button" class="emoji emoji1f367"></span> <span role="button" class="emoji emoji1f368"></span> <span role="button" class="emoji emoji1f366"></span> <span role="button" class="emoji emoji1f370"></span> <span role="button" class="emoji emoji1f382"></span> <span role="button" class="emoji emoji1f9c1"></span> <span role="button" class="emoji emoji1f967"></span> <span role="button" class="emoji emoji1f36e"></span> <span role="button" class="emoji emoji1f36d"></span> <span role="button" class="emoji emoji1f36c"></span> <span role="button" class="emoji emoji1f36b"></span> <span role="button" class="emoji emoji1f37f"></span> <span role="button" class="emoji emoji1f369"></span> <span role="button" class="emoji emoji1f36a"></span> <span role="button" class="emoji emoji1f960"></span> <span role="button" class="emoji emoji1f96e"></span> <span role="button" class="emoji emoji2615"></span> <span role="button" class="emoji emoji1f375"></span> <span role="button" class="emoji emoji1fad6"></span> <span role="button" class="emoji emoji1f963"></span> <span role="button" class="emoji emoji1f37c"></span> <span role="button" class="emoji emoji1f964"></span> <span role="button" class="emoji emoji1f9cb"></span> <span role="button" class="emoji emoji1f9c3"></span> <span role="button" class="emoji emoji1f9c9"></span> <span role="button" class="emoji emoji1f95b"></span> <span role="button" class="emoji emoji1fad7"></span> <span role="button" class="emoji emoji1f37a"></span> <span role="button" class="emoji emoji1f37b"></span> <span role="button" class="emoji emoji1f377"></span> <span role="button" class="emoji emoji1f942"></span> <span role="button" class="emoji emoji1f943"></span> <span role="button" class="emoji emoji1f378"></span> <span role="button" class="emoji emoji1f379"></span> <span role="button" class="emoji emoji1f37e"></span> <span role="button" class="emoji emoji1f376"></span> <span role="button" class="emoji emoji1f9ca"></span> <span role="button" class="emoji emoji1f944"></span> <span role="button" class="emoji emoji1f374"></span> <span role="button" class="emoji emoji1f37d"></span> <span role="button" class="emoji emoji1f962"></span> <span role="button" class="emoji emoji1f961"></span> <span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span>'>
                        </div>
                        <!-- /.emojis -->
                    </div>
                    <!-- /.block -->
                    <script>
                        lister('food', 1);
                    </script>
                    <div id="activity" class="block wait">
                        <a class="tag-list pull-right" href="/emoji/list/activities/" title="lista">≡</a>
                        <h2>
                            <a href="/emoji/list/activities/#emoji-list">Atividades</a>
                        </h2>
                        <div class="emojis" data-cat="activity">
                            <span role="button" class="emoji emoji26bd"></span>
                            <input type='hidden' value='<span role="button" class="emoji emoji1f3c0"></span> <span role="button" class="emoji emoji1f3c8"></span> <span role="button" class="emoji emoji26be"></span> <span role="button" class="emoji emoji1f94e"></span> <span role="button" class="emoji emoji1f3be"></span> <span role="button" class="emoji emoji1f3d0"></span> <span role="button" class="emoji emoji1f3c9"></span> <span role="button" class="emoji emoji1f3b1"></span> <span role="button" class="emoji emoji1f94f"></span> <span role="button" class="emoji emoji1fa83"></span> <span role="button" class="emoji emoji1f3d3"></span> <span role="button" class="emoji emoji1f3f8"></span> <span role="button" class="emoji emoji1f945"></span> <span role="button" class="emoji emoji1f3d2"></span> <span role="button" class="emoji emoji1f3d1"></span> <span role="button" class="emoji emoji1f3cf"></span> <span role="button" class="emoji emoji1f94d"></span> <span role="button" class="emoji emoji1f94c"></span> <span role="button" class="emoji emoji26f3"></span> <span role="button" class="emoji emoji1f3f9"></span> <span role="button" class="emoji emoji1f3a3"></span> <span role="button" class="emoji emoji1f93f"></span> <span role="button" class="emoji emoji1f94a"></span> <span role="button" class="emoji emoji1f94b"></span> <span role="button" class="emoji emoji26f8"></span> <span role="button" class="emoji emoji1f3bf"></span> <span role="button" class="emoji emoji1f6f7"></span> <span role="button" class="emoji emoji26f7"></span> <span role="button" class="emoji emoji1f3c2"></span> <span role="button" class="emoji emoji1f3cb-fe0f-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f3cb"></span> <span role="button" class="emoji emoji1f3cb-fe0f-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f93a"></span> <span role="button" class="emoji emoji1f93c-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f93c"></span> <span role="button" class="emoji emoji1f93c-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f938-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f938"></span> <span role="button" class="emoji emoji1f938-200d-2642-fe0f"></span> <span role="button" class="emoji emoji26f9-fe0f-200d-2640-fe0f"></span> <span role="button" class="emoji emoji26f9"></span> <span role="button" class="emoji emoji26f9-fe0f-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f93e-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f93e"></span> <span role="button" class="emoji emoji1f93e-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f9d7-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f9d7"></span> <span role="button" class="emoji emoji1f9d7-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f3cc-fe0f-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f3cc"></span> <span role="button" class="emoji emoji1f3cc-fe0f-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f9d8-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f9d8"></span> <span role="button" class="emoji emoji1f9d8-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f9d6-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f9d6"></span> <span role="button" class="emoji emoji1f9d6-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f3c4-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f3c4"></span> <span role="button" class="emoji emoji1f3c4-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f3ca-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f3ca"></span> <span role="button" class="emoji emoji1f3ca-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f93d-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f93d"></span> <span role="button" class="emoji emoji1f93d-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f6a3-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f6a3"></span> <span role="button" class="emoji emoji1f6a3-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f3c7"></span> <span role="button" class="emoji emoji1f6b4-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f6b4"></span> <span role="button" class="emoji emoji1f6b4-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f6b5-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f6b5"></span> <span role="button" class="emoji emoji1f6b5-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f3bd"></span> <span role="button" class="emoji emoji1f396"></span> <span role="button" class="emoji emoji1f3c5"></span> <span role="button" class="emoji emoji1f947"></span> <span role="button" class="emoji emoji1f948"></span> <span role="button" class="emoji emoji1f949"></span> <span role="button" class="emoji emoji1f3c6"></span> <span role="button" class="emoji emoji1f3f5"></span> <span role="button" class="emoji emoji1f397"></span> <span role="button" class="emoji emoji1f3ab"></span> <span role="button" class="emoji emoji1f39f"></span> <span role="button" class="emoji emoji1f3aa"></span> <span role="button" class="emoji emoji1f939-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f939"></span> <span role="button" class="emoji emoji1f939-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f3ad"></span> <span role="button" class="emoji emoji1f3a8"></span> <span role="button" class="emoji emoji1f3ac"></span> <span role="button" class="emoji emoji1f3a4"></span> <span role="button" class="emoji emoji1f3a7"></span> <span role="button" class="emoji emoji1f3bc"></span> <span role="button" class="emoji emoji1f3b9"></span> <span role="button" class="emoji emoji1fa97"></span> <span role="button" class="emoji emoji1f941"></span> <span role="button" class="emoji emoji1fa98"></span> <span role="button" class="emoji emoji1f3b7"></span> <span role="button" class="emoji emoji1f3ba"></span> <span role="button" class="emoji emoji1f3b8"></span> <span role="button" class="emoji emoji1fa95"></span> <span role="button" class="emoji emoji1f3bb"></span> <span role="button" class="emoji emoji1f3b2"></span> <span role="button" class="emoji emoji1f9e9"></span> <span role="button" class="emoji emoji265f"></span> <span role="button" class="emoji emoji1f3af"></span> <span role="button" class="emoji emoji1f3b3"></span> <span role="button" class="emoji emoji1fa80"></span> <span role="button" class="emoji emoji1fa81"></span> <span role="button" class="emoji emoji1f6dd"></span> <span role="button" class="emoji emoji1f3ae"></span> <span role="button" class="emoji emoji1f47e"></span> <span role="button" class="emoji emoji1f3b0"></span> <span role="button" class="emoji emoji1f46e-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f46e"></span> <span role="button" class="emoji emoji1f46e-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f469-200d-1f692"></span> <span role="button" class="emoji emoji1f9d1-200d-1f692"></span> <span role="button" class="emoji emoji1f468-200d-1f692"></span> <span role="button" class="emoji emoji1f477-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f477"></span> <span role="button" class="emoji emoji1f477-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f469-200d-1f3ed"></span> <span role="button" class="emoji emoji1f9d1-200d-1f3ed"></span> <span role="button" class="emoji emoji1f468-200d-1f3ed"></span> <span role="button" class="emoji emoji1f469-200d-1f527"></span> <span role="button" class="emoji emoji1f9d1-200d-1f527"></span> <span role="button" class="emoji emoji1f468-200d-1f527"></span> <span role="button" class="emoji emoji1f469-200d-1f33e"></span> <span role="button" class="emoji emoji1f9d1-200d-1f33e"></span> <span role="button" class="emoji emoji1f468-200d-1f33e"></span> <span role="button" class="emoji emoji1f469-200d-1f373"></span> <span role="button" class="emoji emoji1f9d1-200d-1f373"></span> <span role="button" class="emoji emoji1f468-200d-1f373"></span> <span role="button" class="emoji emoji1f469-200d-1f3a4"></span> <span role="button" class="emoji emoji1f9d1-200d-1f3a4"></span> <span role="button" class="emoji emoji1f468-200d-1f3a4"></span> <span role="button" class="emoji emoji1f469-200d-1f3a8"></span> <span role="button" class="emoji emoji1f9d1-200d-1f3a8"></span> <span role="button" class="emoji emoji1f468-200d-1f3a8"></span> <span role="button" class="emoji emoji1f469-200d-1f3eb"></span> <span role="button" class="emoji emoji1f9d1-200d-1f3eb"></span> <span role="button" class="emoji emoji1f468-200d-1f3eb"></span> <span role="button" class="emoji emoji1f469-200d-1f393"></span> <span role="button" class="emoji emoji1f9d1-200d-1f393"></span> <span role="button" class="emoji emoji1f468-200d-1f393"></span> <span role="button" class="emoji emoji1f469-200d-1f4bc"></span> <span role="button" class="emoji emoji1f9d1-200d-1f4bc"></span> <span role="button" class="emoji emoji1f468-200d-1f4bc"></span> <span role="button" class="emoji emoji1f469-200d-1f4bb"></span> <span role="button" class="emoji emoji1f9d1-200d-1f4bb"></span> <span role="button" class="emoji emoji1f468-200d-1f4bb"></span> <span role="button" class="emoji emoji1f469-200d-1f52c"></span> <span role="button" class="emoji emoji1f9d1-200d-1f52c"></span> <span role="button" class="emoji emoji1f468-200d-1f52c"></span> <span role="button" class="emoji emoji1f469-200d-1f680"></span> <span role="button" class="emoji emoji1f9d1-200d-1f680"></span> <span role="button" class="emoji emoji1f468-200d-1f680"></span> <span role="button" class="emoji emoji1f469-200d-2695-fe0f"></span> <span role="button" class="emoji emoji1f9d1-200d-2695-fe0f"></span> <span role="button" class="emoji emoji1f468-200d-2695-fe0f"></span> <span role="button" class="emoji emoji1f469-200d-2696-fe0f"></span> <span role="button" class="emoji emoji1f9d1-200d-2696-fe0f"></span> <span role="button" class="emoji emoji1f468-200d-2696-fe0f"></span> <span role="button" class="emoji emoji1f469-200d-2708-fe0f"></span> <span role="button" class="emoji emoji1f9d1-200d-2708-fe0f"></span> <span role="button" class="emoji emoji1f468-200d-2708-fe0f"></span> <span role="button" class="emoji emoji1f482-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f482"></span> <span role="button" class="emoji emoji1f482-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f977"></span> <span role="button" class="emoji emoji1f575-fe0f-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f575"></span> <span role="button" class="emoji emoji1f575-fe0f-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f936"></span> <span role="button" class="emoji emoji1f9d1-200d-1f384"></span> <span role="button" class="emoji emoji1f385"></span> <span role="button" class="emoji emoji1f574-fe0f-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f574"></span> <span role="button" class="emoji emoji1f574-fe0f-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f9b8-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f9b8"></span> <span role="button" class="emoji emoji1f9b8-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f9b9-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f9b9"></span> <span role="button" class="emoji emoji1f9b9-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f9d9-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f9d9"></span> <span role="button" class="emoji emoji1f9d9-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f9dd-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f9dd"></span> <span role="button" class="emoji emoji1f9dd-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f9da-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f9da"></span> <span role="button" class="emoji emoji1f9da-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f9de-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f9de"></span> <span role="button" class="emoji emoji1f9de-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f9dc-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f9dc"></span> <span role="button" class="emoji emoji1f9dc-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f9cc"></span> <span role="button" class="emoji emoji1f9db-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f9db"></span> <span role="button" class="emoji emoji1f9db-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f9df-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f9df"></span> <span role="button" class="emoji emoji1f9df-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f6b6-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f6b6"></span> <span role="button" class="emoji emoji1f6b6-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f469-200d-1f9af"></span> <span role="button" class="emoji emoji1f9d1-200d-1f9af"></span> <span role="button" class="emoji emoji1f468-200d-1f9af"></span> <span role="button" class="emoji emoji1f3c3-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f3c3"></span> <span role="button" class="emoji emoji1f3c3-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f469-200d-1f9bc"></span> <span role="button" class="emoji emoji1f9d1-200d-1f9bc"></span> <span role="button" class="emoji emoji1f468-200d-1f9bc"></span> <span role="button" class="emoji emoji1f469-200d-1f9bd"></span> <span role="button" class="emoji emoji1f9d1-200d-1f9bd"></span> <span role="button" class="emoji emoji1f468-200d-1f9bd"></span> <span role="button" class="emoji emoji1f46f-200d-2640-fe0f"></span> <span role="button" class="emoji emoji1f46f"></span> <span role="button" class="emoji emoji1f46f-200d-2642-fe0f"></span> <span role="button" class="emoji emoji1f46a"></span> <span role="button" class="emoji emoji1f468-200d-1f469-200d-1f467"></span> <span role="button" class="emoji emoji1f468-200d-1f469-200d-1f467-200d-1f466"></span> <span role="button" class="emoji emoji1f468-200d-1f469-200d-1f466-200d-1f466"></span> <span role="button" class="emoji emoji1f468-200d-1f469-200d-1f467-200d-1f467"></span> <span role="button" class="emoji emoji1f469-200d-1f469-200d-1f466"></span> <span role="button" class="emoji emoji1f469-200d-1f469-200d-1f467"></span> <span role="button" class="emoji emoji1f469-200d-1f469-200d-1f467-200d-1f466"></span> <span role="button" class="emoji emoji1f469-200d-1f469-200d-1f466-200d-1f466"></span> <span role="button" class="emoji emoji1f469-200d-1f469-200d-1f467-200d-1f467"></span> <span role="button" class="emoji emoji1f468-200d-1f468-200d-1f466"></span> <span role="button" class="emoji emoji1f468-200d-1f468-200d-1f467"></span> <span role="button" class="emoji emoji1f468-200d-1f468-200d-1f467-200d-1f466"></span> <span role="button" class="emoji emoji1f468-200d-1f468-200d-1f466-200d-1f466"></span> <span role="button" class="emoji emoji1f468-200d-1f468-200d-1f467-200d-1f467"></span> <span role="button" class="emoji emoji1f469-200d-1f466"></span> <span role="button" class="emoji emoji1f469-200d-1f467"></span> <span role="button" class="emoji emoji1f469-200d-1f467-200d-1f466"></span> <span role="button" class="emoji emoji1f469-200d-1f466-200d-1f466"></span> <span role="button" class="emoji emoji1f469-200d-1f467-200d-1f467"></span> <span role="button" class="emoji emoji1f468-200d-1f466"></span> <span role="button" class="emoji emoji1f468-200d-1f467"></span> <span role="button" class="emoji emoji1f468-200d-1f467-200d-1f466"></span> <span role="button" class="emoji emoji1f468-200d-1f466-200d-1f466"></span> <span role="button" class="emoji emoji1f468-200d-1f467-200d-1f467"></span> <span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span>'>
                        </div>
                        <!-- /.emojis -->
                    </div>
                    <!-- /.block -->
                    <script>
                        lister('activity', 1);
                    </script>
                    <div id="travel" class="block wait">
                        <a class="tag-list pull-right" href="/emoji/list/travel-places/" title="lista">≡</a>
                        <h2>
                            <a href="/emoji/list/travel-places/#emoji-list">Viagem e locais</a>
                        </h2>
                        <div class="emojis" data-cat="travel">
                            <span role="button" class="emoji emoji1f697"></span>
                            <input type='hidden' value='<span role="button" class="emoji emoji1f699"></span> <span role="button" class="emoji emoji1f695"></span> <span role="button" class="emoji emoji1f6fa"></span> <span role="button" class="emoji emoji1f68c"></span> <span role="button" class="emoji emoji1f68e"></span> <span role="button" class="emoji emoji1f3ce"></span> <span role="button" class="emoji emoji1f693"></span> <span role="button" class="emoji emoji1f691"></span> <span role="button" class="emoji emoji1f692"></span> <span role="button" class="emoji emoji1f690"></span> <span role="button" class="emoji emoji1f6fb"></span> <span role="button" class="emoji emoji1f69a"></span> <span role="button" class="emoji emoji1f69b"></span> <span role="button" class="emoji emoji1f69c"></span> <span role="button" class="emoji emoji1f3cd"></span> <span role="button" class="emoji emoji1f6f5"></span> <span role="button" class="emoji emoji1f6b2"></span> <span role="button" class="emoji emoji1f9bc"></span> <span role="button" class="emoji emoji1f9bd"></span> <span role="button" class="emoji emoji1f6f4"></span> <span role="button" class="emoji emoji1f6f9"></span> <span role="button" class="emoji emoji1f6fc"></span> <span role="button" class="emoji emoji1f6de"></span> <span role="button" class="emoji emoji1f6a8"></span> <span role="button" class="emoji emoji1f694"></span> <span role="button" class="emoji emoji1f68d"></span> <span role="button" class="emoji emoji1f698"></span> <span role="button" class="emoji emoji1f696"></span> <span role="button" class="emoji emoji1f6a1"></span> <span role="button" class="emoji emoji1f6a0"></span> <span role="button" class="emoji emoji1f69f"></span> <span role="button" class="emoji emoji1f683"></span> <span role="button" class="emoji emoji1f68b"></span> <span role="button" class="emoji emoji1f69d"></span> <span role="button" class="emoji emoji1f684"></span> <span role="button" class="emoji emoji1f685"></span> <span role="button" class="emoji emoji1f688"></span> <span role="button" class="emoji emoji1f69e"></span> <span role="button" class="emoji emoji1f682"></span> <span role="button" class="emoji emoji1f686"></span> <span role="button" class="emoji emoji1f687"></span> <span role="button" class="emoji emoji1f68a"></span> <span role="button" class="emoji emoji1f689"></span> <span role="button" class="emoji emoji1f681"></span> <span role="button" class="emoji emoji1f6e9"></span> <span role="button" class="emoji emoji2708"></span> <span role="button" class="emoji emoji1f6eb"></span> <span role="button" class="emoji emoji1f6ec"></span> <span role="button" class="emoji emoji1fa82"></span> <span role="button" class="emoji emoji1f4ba"></span> <span role="button" class="emoji emoji1f6f0"></span> <span role="button" class="emoji emoji1f680"></span> <span role="button" class="emoji emoji1f6f8"></span> <span role="button" class="emoji emoji1f6f6"></span> <span role="button" class="emoji emoji26f5"></span> <span role="button" class="emoji emoji1f6e5"></span> <span role="button" class="emoji emoji1f6a4"></span> <span role="button" class="emoji emoji26f4"></span> <span role="button" class="emoji emoji1f6f3"></span> <span role="button" class="emoji emoji1f6a2"></span> <span role="button" class="emoji emoji1f6df"></span> <span role="button" class="emoji emoji2693"></span> <span role="button" class="emoji emoji26fd"></span> <span role="button" class="emoji emoji1f6a7"></span> <span role="button" class="emoji emoji1f68f"></span> <span role="button" class="emoji emoji1f6a6"></span> <span role="button" class="emoji emoji1f6a5"></span> <span role="button" class="emoji emoji1f6d1"></span> <span role="button" class="emoji emoji1f3a1"></span> <span role="button" class="emoji emoji1f3a2"></span> <span role="button" class="emoji emoji1f3a0"></span> <span role="button" class="emoji emoji1f3d7"></span> <span role="button" class="emoji emoji1f301"></span> <span role="button" class="emoji emoji1f5fc"></span> <span role="button" class="emoji emoji1f3ed"></span> <span role="button" class="emoji emoji26f2"></span> <span role="button" class="emoji emoji1f391"></span> <span role="button" class="emoji emoji26f0"></span> <span role="button" class="emoji emoji1f3d4"></span> <span role="button" class="emoji emoji1f5fb"></span> <span role="button" class="emoji emoji1f30b"></span> <span role="button" class="emoji emoji1f5fe"></span> <span role="button" class="emoji emoji1f3d5"></span> <span role="button" class="emoji emoji26fa"></span> <span role="button" class="emoji emoji1f3de"></span> <span role="button" class="emoji emoji1f6e3"></span> <span role="button" class="emoji emoji1f6e4"></span> <span role="button" class="emoji emoji1f305"></span> <span role="button" class="emoji emoji1f304"></span> <span role="button" class="emoji emoji1f3dc"></span> <span role="button" class="emoji emoji1f3d6"></span> <span role="button" class="emoji emoji1f3dd"></span> <span role="button" class="emoji emoji1f307"></span> <span role="button" class="emoji emoji1f306"></span> <span role="button" class="emoji emoji1f3d9"></span> <span role="button" class="emoji emoji1f303"></span> <span role="button" class="emoji emoji1f309"></span> <span role="button" class="emoji emoji1f30c"></span> <span role="button" class="emoji emoji1f320"></span> <span role="button" class="emoji emoji1f387"></span> <span role="button" class="emoji emoji1f386"></span> <span role="button" class="emoji emoji1f6d6"></span> <span role="button" class="emoji emoji1f3d8"></span> <span role="button" class="emoji emoji1f3f0"></span> <span role="button" class="emoji emoji1f3ef"></span> <span role="button" class="emoji emoji1f3df"></span> <span role="button" class="emoji emoji1f5fd"></span> <span role="button" class="emoji emoji1f3e0"></span> <span role="button" class="emoji emoji1f3e1"></span> <span role="button" class="emoji emoji1f3da"></span> <span role="button" class="emoji emoji1f3e2"></span> <span role="button" class="emoji emoji1f3ec"></span> <span role="button" class="emoji emoji1f3e3"></span> <span role="button" class="emoji emoji1f3e4"></span> <span role="button" class="emoji emoji1f3e5"></span> <span role="button" class="emoji emoji1f3e6"></span> <span role="button" class="emoji emoji1f3e8"></span> <span role="button" class="emoji emoji1f3ea"></span> <span role="button" class="emoji emoji1f3eb"></span> <span role="button" class="emoji emoji1f3e9"></span> <span role="button" class="emoji emoji1f492"></span> <span role="button" class="emoji emoji1f3db"></span> <span role="button" class="emoji emoji26ea"></span> <span role="button" class="emoji emoji1f54c"></span> <span role="button" class="emoji emoji1f6d5"></span> <span role="button" class="emoji emoji1f54d"></span> <span role="button" class="emoji emoji1f54b"></span> <span role="button" class="emoji emoji26e9"></span> <span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span>'>
                        </div>
                        <!-- /.emojis -->
                    </div>
                    <!-- /.block -->
                    <script>
                        lister('travel', 1);
                    </script>
                    <div id="dfp-2" class='ads ads-728x90 idx-2' style='width:728px;height:90px'>
                        <script>
                            googletag.cmd.push(function() {
                                googletag.display('dfp-2');
                            });
                        </script>
                    </div>
                    <div id="objects" class="block wait">
                        <a class="tag-list pull-right" href="/emoji/list/objects/" title="lista">≡</a>
                        <h2>
                            <a href="/emoji/list/objects/#emoji-list">Objetos</a>
                        </h2>
                        <div class="emojis" data-cat="objects">
                            <span role="button" class="emoji emoji231a"></span>
                            <input type='hidden' value='<span role="button" class="emoji emoji1f4f1"></span> <span role="button" class="emoji emoji1f4f2"></span> <span role="button" class="emoji emoji1f4bb"></span> <span role="button" class="emoji emoji2328"></span> <span role="button" class="emoji emoji1f5a5"></span> <span role="button" class="emoji emoji1f5a8"></span> <span role="button" class="emoji emoji1f5b1"></span> <span role="button" class="emoji emoji1f5b2"></span> <span role="button" class="emoji emoji1f579"></span> <span role="button" class="emoji emoji1f5dc"></span> <span role="button" class="emoji emoji1f4bd"></span> <span role="button" class="emoji emoji1f4be"></span> <span role="button" class="emoji emoji1f4bf"></span> <span role="button" class="emoji emoji1f4c0"></span> <span role="button" class="emoji emoji1f4fc"></span> <span role="button" class="emoji emoji1f4f7"></span> <span role="button" class="emoji emoji1f4f8"></span> <span role="button" class="emoji emoji1f4f9"></span> <span role="button" class="emoji emoji1f3a5"></span> <span role="button" class="emoji emoji1f4fd"></span> <span role="button" class="emoji emoji1f39e"></span> <span role="button" class="emoji emoji1f4de"></span> <span role="button" class="emoji emoji260e"></span> <span role="button" class="emoji emoji1f4df"></span> <span role="button" class="emoji emoji1f4e0"></span> <span role="button" class="emoji emoji1f4fa"></span> <span role="button" class="emoji emoji1f4fb"></span> <span role="button" class="emoji emoji1f399"></span> <span role="button" class="emoji emoji1f39a"></span> <span role="button" class="emoji emoji1f39b"></span> <span role="button" class="emoji emoji23f1"></span> <span role="button" class="emoji emoji23f2"></span> <span role="button" class="emoji emoji23f0"></span> <span role="button" class="emoji emoji1f570"></span> <span role="button" class="emoji emoji23f3"></span> <span role="button" class="emoji emoji231b"></span> <span role="button" class="emoji emoji1f9ee"></span> <span role="button" class="emoji emoji1f4e1"></span> <span role="button" class="emoji emoji1f50b"></span> <span role="button" class="emoji emoji1faab"></span> <span role="button" class="emoji emoji1f50c"></span> <span role="button" class="emoji emoji1f4a1"></span> <span role="button" class="emoji emoji1f526"></span> <span role="button" class="emoji emoji1f56f"></span> <span role="button" class="emoji emoji1f9ef"></span> <span role="button" class="emoji emoji1f5d1"></span> <span role="button" class="emoji emoji1f6e2"></span> <span role="button" class="emoji emoji1f6d2"></span> <span role="button" class="emoji emoji1f4b8"></span> <span role="button" class="emoji emoji1f4b5"></span> <span role="button" class="emoji emoji1f4b4"></span> <span role="button" class="emoji emoji1f4b6"></span> <span role="button" class="emoji emoji1f4b7"></span> <span role="button" class="emoji emoji1f4b0"></span> <span role="button" class="emoji emoji1fa99"></span> <span role="button" class="emoji emoji1f4b3"></span> <span role="button" class="emoji emoji1faaa"></span> <span role="button" class="emoji emoji1f9fe"></span> <span role="button" class="emoji emoji1f48e"></span> <span role="button" class="emoji emoji2696"></span> <span role="button" class="emoji emoji1f9af"></span> <span role="button" class="emoji emoji1f9f0"></span> <span role="button" class="emoji emoji1f527"></span> <span role="button" class="emoji emoji1fa9b"></span> <span role="button" class="emoji emoji1f528"></span> <span role="button" class="emoji emoji2692"></span> <span role="button" class="emoji emoji1f6e0"></span> <span role="button" class="emoji emoji26cf"></span> <span role="button" class="emoji emoji1fa93"></span> <span role="button" class="emoji emoji1fa9a"></span> <span role="button" class="emoji emoji1f529"></span> <span role="button" class="emoji emoji2699"></span> <span role="button" class="emoji emoji26d3"></span> <span role="button" class="emoji emoji1fa9d"></span> <span role="button" class="emoji emoji1fa9c"></span> <span role="button" class="emoji emoji1f9f1"></span> <span role="button" class="emoji emoji1faa8"></span> <span role="button" class="emoji emoji1fab5"></span> <span role="button" class="emoji emoji1f52b"></span> <span role="button" class="emoji emoji1f9e8"></span> <span role="button" class="emoji emoji1f4a3"></span> <span role="button" class="emoji emoji1f52a"></span> <span role="button" class="emoji emoji1f5e1"></span> <span role="button" class="emoji emoji2694"></span> <span role="button" class="emoji emoji1f6e1"></span> <span role="button" class="emoji emoji1f6ac"></span> <span role="button" class="emoji emoji26b0"></span> <span role="button" class="emoji emoji1faa6"></span> <span role="button" class="emoji emoji26b1"></span> <span role="button" class="emoji emoji1f3fa"></span> <span role="button" class="emoji emoji1f52e"></span> <span role="button" class="emoji emoji1fa84"></span> <span role="button" class="emoji emoji1f4ff"></span> <span role="button" class="emoji emoji1f9ff"></span> <span role="button" class="emoji emoji1faac"></span> <span role="button" class="emoji emoji1f488"></span> <span role="button" class="emoji emoji1f9f2"></span> <span role="button" class="emoji emoji2697"></span> <span role="button" class="emoji emoji1f9ea"></span> <span role="button" class="emoji emoji1f9eb"></span> <span role="button" class="emoji emoji1f9ec"></span> <span role="button" class="emoji emoji1f52d"></span> <span role="button" class="emoji emoji1f52c"></span> <span role="button" class="emoji emoji1f573"></span> <span role="button" class="emoji emoji1fa7b"></span> <span role="button" class="emoji emoji1f48a"></span> <span role="button" class="emoji emoji1f489"></span> <span role="button" class="emoji emoji1fa78"></span> <span role="button" class="emoji emoji1fa79"></span> <span role="button" class="emoji emoji1fa7a"></span> <span role="button" class="emoji emoji1f321"></span> <span role="button" class="emoji emoji1fa7c"></span> <span role="button" class="emoji emoji1f3f7"></span> <span role="button" class="emoji emoji1f516"></span> <span role="button" class="emoji emoji1f6bd"></span> <span role="button" class="emoji emoji1faa0"></span> <span role="button" class="emoji emoji1f6bf"></span> <span role="button" class="emoji emoji1f6c1"></span> <span role="button" class="emoji emoji1f6c0"></span> <span role="button" class="emoji emoji1faa5"></span> <span role="button" class="emoji emoji1fa92"></span> <span role="button" class="emoji emoji1f9f4"></span> <span role="button" class="emoji emoji1f9fb"></span> <span role="button" class="emoji emoji1f9fc"></span> <span role="button" class="emoji emoji1fae7"></span> <span role="button" class="emoji emoji1f9fd"></span> <span role="button" class="emoji emoji1f9f9"></span> <span role="button" class="emoji emoji1f9fa"></span> <span role="button" class="emoji emoji1faa3"></span> <span role="button" class="emoji emoji1f511"></span> <span role="button" class="emoji emoji1f5dd"></span> <span role="button" class="emoji emoji1faa4"></span> <span role="button" class="emoji emoji1f6cb"></span> <span role="button" class="emoji emoji1fa91"></span> <span role="button" class="emoji emoji1f6cc"></span> <span role="button" class="emoji emoji1f6cf"></span> <span role="button" class="emoji emoji1f6aa"></span> <span role="button" class="emoji emoji1fa9e"></span> <span role="button" class="emoji emoji1fa9f"></span> <span role="button" class="emoji emoji1f9f3"></span> <span role="button" class="emoji emoji1f6ce"></span> <span role="button" class="emoji emoji1f5bc"></span> <span role="button" class="emoji emoji1f9ed"></span> <span role="button" class="emoji emoji1f5fa"></span> <span role="button" class="emoji emoji26f1"></span> <span role="button" class="emoji emoji1f5ff"></span> <span role="button" class="emoji emoji1f6cd"></span> <span role="button" class="emoji emoji1f388"></span> <span role="button" class="emoji emoji1f38f"></span> <span role="button" class="emoji emoji1f380"></span> <span role="button" class="emoji emoji1f9e7"></span> <span role="button" class="emoji emoji1f381"></span> <span role="button" class="emoji emoji1f38a"></span> <span role="button" class="emoji emoji1f389"></span> <span role="button" class="emoji emoji1fa85"></span> <span role="button" class="emoji emoji1faa9"></span> <span role="button" class="emoji emoji1fa86"></span> <span role="button" class="emoji emoji1f38e"></span> <span role="button" class="emoji emoji1f390"></span> <span role="button" class="emoji emoji1f3ee"></span> <span role="button" class="emoji emoji1fa94"></span> <span role="button" class="emoji emoji2709"></span> <span role="button" class="emoji emoji1f4e9"></span> <span role="button" class="emoji emoji1f4e8"></span> <span role="button" class="emoji emoji1f4e7"></span> <span role="button" class="emoji emoji1f48c"></span> <span role="button" class="emoji emoji1f4ee"></span> <span role="button" class="emoji emoji1f4ea"></span> <span role="button" class="emoji emoji1f4eb"></span> <span role="button" class="emoji emoji1f4ec"></span> <span role="button" class="emoji emoji1f4ed"></span> <span role="button" class="emoji emoji1f4e6"></span> <span role="button" class="emoji emoji1f4ef"></span> <span role="button" class="emoji emoji1f4e5"></span> <span role="button" class="emoji emoji1f4e4"></span> <span role="button" class="emoji emoji1f4dc"></span> <span role="button" class="emoji emoji1f4c3"></span> <span role="button" class="emoji emoji1f4d1"></span> <span role="button" class="emoji emoji1f4ca"></span> <span role="button" class="emoji emoji1f4c8"></span> <span role="button" class="emoji emoji1f4c9"></span> <span role="button" class="emoji emoji1f4c4"></span> <span role="button" class="emoji emoji1f4c5"></span> <span role="button" class="emoji emoji1f4c6"></span> <span role="button" class="emoji emoji1f5d3"></span> <span role="button" class="emoji emoji1f4c7"></span> <span role="button" class="emoji emoji1f5c3"></span> <span role="button" class="emoji emoji1f5f3"></span> <span role="button" class="emoji emoji1f5c4"></span> <span role="button" class="emoji emoji1f4cb"></span> <span role="button" class="emoji emoji1f5d2"></span> <span role="button" class="emoji emoji1f4c1"></span> <span role="button" class="emoji emoji1f4c2"></span> <span role="button" class="emoji emoji1f5c2"></span> <span role="button" class="emoji emoji1f5de"></span> <span role="button" class="emoji emoji1f4f0"></span> <span role="button" class="emoji emoji1faa7"></span> <span role="button" class="emoji emoji1f4d3"></span> <span role="button" class="emoji emoji1f4d5"></span> <span role="button" class="emoji emoji1f4d7"></span> <span role="button" class="emoji emoji1f4d8"></span> <span role="button" class="emoji emoji1f4d9"></span> <span role="button" class="emoji emoji1f4d4"></span> <span role="button" class="emoji emoji1f4d2"></span> <span role="button" class="emoji emoji1f4da"></span> <span role="button" class="emoji emoji1f4d6"></span> <span role="button" class="emoji emoji1f517"></span> <span role="button" class="emoji emoji1f4ce"></span> <span role="button" class="emoji emoji1f587"></span> <span role="button" class="emoji emoji2702"></span> <span role="button" class="emoji emoji1f4d0"></span> <span role="button" class="emoji emoji1f4cf"></span> <span role="button" class="emoji emoji1f4cc"></span> <span role="button" class="emoji emoji1f4cd"></span> <span role="button" class="emoji emoji1f9f7"></span> <span role="button" class="emoji emoji1faa1"></span> <span role="button" class="emoji emoji1f9f5"></span> <span role="button" class="emoji emoji1f9f6"></span> <span role="button" class="emoji emoji1faa2"></span> <span role="button" class="emoji emoji1f510"></span> <span role="button" class="emoji emoji1f512"></span> <span role="button" class="emoji emoji1f513"></span> <span role="button" class="emoji emoji1f50f"></span> <span role="button" class="emoji emoji1f58a"></span> <span role="button" class="emoji emoji1f58b"></span> <span role="button" class="emoji emoji2712"></span> <span role="button" class="emoji emoji1f4dd"></span> <span role="button" class="emoji emoji270f"></span> <span role="button" class="emoji emoji1f58d"></span> <span role="button" class="emoji emoji1f58c"></span> <span role="button" class="emoji emoji1f50d"></span> <span role="button" class="emoji emoji1f50e"></span> <span role="button" class="emoji emoji1f45a"></span> <span role="button" class="emoji emoji1f455"></span> <span role="button" class="emoji emoji1f97c"></span> <span role="button" class="emoji emoji1f9ba"></span> <span role="button" class="emoji emoji1f9e5"></span> <span role="button" class="emoji emoji1f456"></span> <span role="button" class="emoji emoji1f454"></span> <span role="button" class="emoji emoji1f457"></span> <span role="button" class="emoji emoji1f458"></span> <span role="button" class="emoji emoji1f97b"></span> <span role="button" class="emoji emoji1fa71"></span> <span role="button" class="emoji emoji1f459"></span> <span role="button" class="emoji emoji1fa72"></span> <span role="button" class="emoji emoji1fa73"></span> <span role="button" class="emoji emoji1f484"></span> <span role="button" class="emoji emoji1f48b"></span> <span role="button" class="emoji emoji1f463"></span> <span role="button" class="emoji emoji1f9e6"></span> <span role="button" class="emoji emoji1fa74"></span> <span role="button" class="emoji emoji1f460"></span> <span role="button" class="emoji emoji1f461"></span> <span role="button" class="emoji emoji1f462"></span> <span role="button" class="emoji emoji1f97f"></span> <span role="button" class="emoji emoji1f45e"></span> <span role="button" class="emoji emoji1f45f"></span> <span role="button" class="emoji emoji1fa70"></span> <span role="button" class="emoji emoji1f97e"></span> <span role="button" class="emoji emoji1f9e2"></span> <span role="button" class="emoji emoji1f452"></span> <span role="button" class="emoji emoji1f3a9"></span> <span role="button" class="emoji emoji1f393"></span> <span role="button" class="emoji emoji1f451"></span> <span role="button" class="emoji emoji26d1"></span> <span role="button" class="emoji emoji1fa96"></span> <span role="button" class="emoji emoji1f392"></span> <span role="button" class="emoji emoji1f45d"></span> <span role="button" class="emoji emoji1f45b"></span> <span role="button" class="emoji emoji1f45c"></span> <span role="button" class="emoji emoji1f4bc"></span> <span role="button" class="emoji emoji1f453"></span> <span role="button" class="emoji emoji1f576"></span> <span role="button" class="emoji emoji1f97d"></span> <span role="button" class="emoji emoji1f9e3"></span> <span role="button" class="emoji emoji1f9e4"></span> <span role="button" class="emoji emoji1f48d"></span> <span role="button" class="emoji emoji1f302"></span> <span role="button" class="emoji emoji2602"></span> <span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span>'>
                        </div>
                        <!-- /.emojis -->
                    </div>
                    <!-- /.block -->
                    <script>
                        lister('objects', 1);
                    </script>
                    <div id="symbols" class="block wait">
                        <a class="tag-list pull-right" href="/emoji/list/symbols/" title="lista">≡</a>
                        <h2>
                            <a href="/emoji/list/symbols/#emoji-list">Símbolos</a>
                        </h2>
                        <div class="emojis" data-cat="symbols">
                            <span role="button" class="emoji emoji262e"></span>
                            <input type='hidden' value='<span role="button" class="emoji emoji271d"></span> <span role="button" class="emoji emoji262a"></span> <span role="button" class="emoji emoji1f549"></span> <span role="button" class="emoji emoji2638"></span> <span role="button" class="emoji emoji2721"></span> <span role="button" class="emoji emoji1f52f"></span> <span role="button" class="emoji emoji1f54e"></span> <span role="button" class="emoji emoji262f"></span> <span role="button" class="emoji emoji2626"></span> <span role="button" class="emoji emoji1f6d0"></span> <span role="button" class="emoji emoji26ce"></span> <span role="button" class="emoji emoji2648"></span> <span role="button" class="emoji emoji2649"></span> <span role="button" class="emoji emoji264a"></span> <span role="button" class="emoji emoji264b"></span> <span role="button" class="emoji emoji264c"></span> <span role="button" class="emoji emoji264d"></span> <span role="button" class="emoji emoji264e"></span> <span role="button" class="emoji emoji264f"></span> <span role="button" class="emoji emoji2650"></span> <span role="button" class="emoji emoji2651"></span> <span role="button" class="emoji emoji2652"></span> <span role="button" class="emoji emoji2653"></span> <span role="button" class="emoji emoji1f194"></span> <span role="button" class="emoji emoji269b"></span> <span role="button" class="emoji emoji2695"></span> <span role="button" class="emoji emoji2622"></span> <span role="button" class="emoji emoji2623"></span> <span role="button" class="emoji emoji1f4f4"></span> <span role="button" class="emoji emoji1f4f3"></span> <span role="button" class="emoji emoji1f236"></span> <span role="button" class="emoji emoji1f21a"></span> <span role="button" class="emoji emoji1f238"></span> <span role="button" class="emoji emoji1f23a"></span> <span role="button" class="emoji emoji1f237"></span> <span role="button" class="emoji emoji2734"></span> <span role="button" class="emoji emoji1f19a"></span> <span role="button" class="emoji emoji1f251"></span> <span role="button" class="emoji emoji1f4ae"></span> <span role="button" class="emoji emoji1f250"></span> <span role="button" class="emoji emoji3299"></span> <span role="button" class="emoji emoji3297"></span> <span role="button" class="emoji emoji1f234"></span> <span role="button" class="emoji emoji1f235"></span> <span role="button" class="emoji emoji1f239"></span> <span role="button" class="emoji emoji1f232"></span> <span role="button" class="emoji emoji1f170"></span> <span role="button" class="emoji emoji1f171"></span> <span role="button" class="emoji emoji1f18e"></span> <span role="button" class="emoji emoji1f191"></span> <span role="button" class="emoji emoji1f17e"></span> <span role="button" class="emoji emoji1f198"></span> <span role="button" class="emoji emoji26d4"></span> <span role="button" class="emoji emoji1f4db"></span> <span role="button" class="emoji emoji1f6ab"></span> <span role="button" class="emoji emoji274c"></span> <span role="button" class="emoji emoji2b55"></span> <span role="button" class="emoji emoji1f4a2"></span> <span role="button" class="emoji emoji2668"></span> <span role="button" class="emoji emoji1f6b7"></span> <span role="button" class="emoji emoji1f6af"></span> <span role="button" class="emoji emoji1f6b3"></span> <span role="button" class="emoji emoji1f6b1"></span> <span role="button" class="emoji emoji1f51e"></span> <span role="button" class="emoji emoji1f4f5"></span> <span role="button" class="emoji emoji1f6ad"></span> <span role="button" class="emoji emoji2757"></span> <span role="button" class="emoji emoji2755"></span> <span role="button" class="emoji emoji2753"></span> <span role="button" class="emoji emoji2754"></span> <span role="button" class="emoji emoji203c"></span> <span role="button" class="emoji emoji2049"></span> <span role="button" class="emoji emoji1f4af"></span> <span role="button" class="emoji emoji1f505"></span> <span role="button" class="emoji emoji1f506"></span> <span role="button" class="emoji emoji1f531"></span> <span role="button" class="emoji emoji269c"></span> <span role="button" class="emoji emoji303d"></span> <span role="button" class="emoji emoji26a0"></span> <span role="button" class="emoji emoji1f6b8"></span> <span role="button" class="emoji emoji1f530"></span> <span role="button" class="emoji emoji267b"></span> <span role="button" class="emoji emoji1f22f"></span> <span role="button" class="emoji emoji1f4b9"></span> <span role="button" class="emoji emoji2747"></span> <span role="button" class="emoji emoji2733"></span> <span role="button" class="emoji emoji274e"></span> <span role="button" class="emoji emoji2705"></span> <span role="button" class="emoji emoji1f4a0"></span> <span role="button" class="emoji emoji1f300"></span> <span role="button" class="emoji emoji27bf"></span> <span role="button" class="emoji emoji1f310"></span> <span role="button" class="emoji emoji267e"></span> <span role="button" class="emoji emoji24c2"></span> <span role="button" class="emoji emoji1f3e7"></span> <span role="button" class="emoji emoji1f6be"></span> <span role="button" class="emoji emoji267f"></span> <span role="button" class="emoji emoji1f17f"></span> <span role="button" class="emoji emoji1f233"></span> <span role="button" class="emoji emoji1f202"></span> <span role="button" class="emoji emoji1f6c2"></span> <span role="button" class="emoji emoji1f6c3"></span> <span role="button" class="emoji emoji1f6c4"></span> <span role="button" class="emoji emoji1f6c5"></span> <span role="button" class="emoji emoji1f6b0"></span> <span role="button" class="emoji emoji1f6d7"></span> <span role="button" class="emoji emoji1f6b9"></span> <span role="button" class="emoji emoji2642"></span> <span role="button" class="emoji emoji1f6ba"></span> <span role="button" class="emoji emoji2640"></span> <span role="button" class="emoji emoji26a7"></span> <span role="button" class="emoji emoji1f6bc"></span> <span role="button" class="emoji emoji1f6bb"></span> <span role="button" class="emoji emoji1f6ae"></span> <span role="button" class="emoji emoji1f3a6"></span> <span role="button" class="emoji emoji1f4f6"></span> <span role="button" class="emoji emoji1f201"></span> <span role="button" class="emoji emoji1f196"></span> <span role="button" class="emoji emoji1f197"></span> <span role="button" class="emoji emoji1f199"></span> <span role="button" class="emoji emoji1f192"></span> <span role="button" class="emoji emoji1f195"></span> <span role="button" class="emoji emoji1f193"></span> <span role="button" class="emoji emoji30-20e3"></span> <span role="button" class="emoji emoji31-20e3"></span> <span role="button" class="emoji emoji32-20e3"></span> <span role="button" class="emoji emoji33-20e3"></span> <span role="button" class="emoji emoji34-20e3"></span> <span role="button" class="emoji emoji35-20e3"></span> <span role="button" class="emoji emoji36-20e3"></span> <span role="button" class="emoji emoji37-20e3"></span> <span role="button" class="emoji emoji38-20e3"></span> <span role="button" class="emoji emoji39-20e3"></span> <span role="button" class="emoji emoji1f51f"></span> <span role="button" class="emoji emoji1f522"></span> <span role="button" class="emoji emoji25b6"></span> <span role="button" class="emoji emoji23f8"></span> <span role="button" class="emoji emoji23ef"></span> <span role="button" class="emoji emoji23f9"></span> <span role="button" class="emoji emoji23fa"></span> <span role="button" class="emoji emoji23cf"></span> <span role="button" class="emoji emoji23ed"></span> <span role="button" class="emoji emoji23ee"></span> <span role="button" class="emoji emoji23e9"></span> <span role="button" class="emoji emoji23ea"></span> <span role="button" class="emoji emoji1f500"></span> <span role="button" class="emoji emoji1f501"></span> <span role="button" class="emoji emoji1f502"></span> <span role="button" class="emoji emoji25c0"></span> <span role="button" class="emoji emoji1f53c"></span> <span role="button" class="emoji emoji1f53d"></span> <span role="button" class="emoji emoji23eb"></span> <span role="button" class="emoji emoji23ec"></span> <span role="button" class="emoji emoji27a1"></span> <span role="button" class="emoji emoji2b05"></span> <span role="button" class="emoji emoji2b06"></span> <span role="button" class="emoji emoji2b07"></span> <span role="button" class="emoji emoji2197"></span> <span role="button" class="emoji emoji2198"></span> <span role="button" class="emoji emoji2199"></span> <span role="button" class="emoji emoji2196"></span> <span role="button" class="emoji emoji2195"></span> <span role="button" class="emoji emoji2194"></span> <span role="button" class="emoji emoji1f504"></span> <span role="button" class="emoji emoji21aa"></span> <span role="button" class="emoji emoji21a9"></span> <span role="button" class="emoji emoji1f503"></span> <span role="button" class="emoji emoji2934"></span> <span role="button" class="emoji emoji2935"></span> <span role="button" class="emoji emoji23-20e3"></span> <span role="button" class="emoji emoji2a-20e3"></span> <span role="button" class="emoji emoji2139"></span> <span role="button" class="emoji emoji1f524"></span> <span role="button" class="emoji emoji1f521"></span> <span role="button" class="emoji emoji1f520"></span> <span role="button" class="emoji emoji1f523"></span> <span role="button" class="emoji emoji1f3b5"></span> <span role="button" class="emoji emoji1f3b6"></span> <span role="button" class="emoji emoji3030"></span> <span role="button" class="emoji emoji27b0"></span> <span role="button" class="emoji emoji2714"></span> <span role="button" class="emoji emoji2795"></span> <span role="button" class="emoji emoji2796"></span> <span role="button" class="emoji emoji2797"></span> <span role="button" class="emoji emoji2716"></span> <span role="button" class="emoji emoji1f7f0"></span> <span role="button" class="emoji emoji1f4b2"></span> <span role="button" class="emoji emoji1f4b1"></span> <span role="button" class="emoji emojia9"></span> <span role="button" class="emoji emojiae"></span> <span role="button" class="emoji emoji2122"></span> <span role="button" class="emoji emoji1f51a"></span> <span role="button" class="emoji emoji1f519"></span> <span role="button" class="emoji emoji1f51b"></span> <span role="button" class="emoji emoji1f51d"></span> <span role="button" class="emoji emoji1f51c"></span> <span role="button" class="emoji emoji2611"></span> <span role="button" class="emoji emoji1f518"></span> <span role="button" class="emoji emoji1f534"></span> <span role="button" class="emoji emoji1f7e0"></span> <span role="button" class="emoji emoji1f7e1"></span> <span role="button" class="emoji emoji1f7e2"></span> <span role="button" class="emoji emoji1f535"></span> <span role="button" class="emoji emoji1f7e3"></span> <span role="button" class="emoji emoji1f7e4"></span> <span role="button" class="emoji emoji26ab"></span> <span role="button" class="emoji emoji26aa"></span> <span role="button" class="emoji emoji1f7e5"></span> <span role="button" class="emoji emoji1f7e7"></span> <span role="button" class="emoji emoji1f7e8"></span> <span role="button" class="emoji emoji1f7e9"></span> <span role="button" class="emoji emoji1f7e6"></span> <span role="button" class="emoji emoji1f7ea"></span> <span role="button" class="emoji emoji1f7eb"></span> <span role="button" class="emoji emoji2b1b"></span> <span role="button" class="emoji emoji2b1c"></span> <span role="button" class="emoji emoji25fc"></span> <span role="button" class="emoji emoji25fb"></span> <span role="button" class="emoji emoji25fe"></span> <span role="button" class="emoji emoji25fd"></span> <span role="button" class="emoji emoji25aa"></span> <span role="button" class="emoji emoji25ab"></span> <span role="button" class="emoji emoji1f538"></span> <span role="button" class="emoji emoji1f539"></span> <span role="button" class="emoji emoji1f536"></span> <span role="button" class="emoji emoji1f537"></span> <span role="button" class="emoji emoji1f53a"></span> <span role="button" class="emoji emoji1f53b"></span> <span role="button" class="emoji emoji1f532"></span> <span role="button" class="emoji emoji1f533"></span> <span role="button" class="emoji emoji1f508"></span> <span role="button" class="emoji emoji1f509"></span> <span role="button" class="emoji emoji1f50a"></span> <span role="button" class="emoji emoji1f507"></span> <span role="button" class="emoji emoji1f4e3"></span> <span role="button" class="emoji emoji1f4e2"></span> <span role="button" class="emoji emoji1f514"></span> <span role="button" class="emoji emoji1f515"></span> <span role="button" class="emoji emoji1f0cf"></span> <span role="button" class="emoji emoji1f004"></span> <span role="button" class="emoji emoji2660"></span> <span role="button" class="emoji emoji2663"></span> <span role="button" class="emoji emoji2665"></span> <span role="button" class="emoji emoji2666"></span> <span role="button" class="emoji emoji1f3b4"></span> <span role="button" class="emoji emoji1f441-200d-1f5e8"></span> <span role="button" class="emoji emoji1f5e8"></span> <span role="button" class="emoji emoji1f4ad"></span> <span role="button" class="emoji emoji1f5ef"></span> <span role="button" class="emoji emoji1f4ac"></span> <span role="button" class="emoji emoji1f550"></span> <span role="button" class="emoji emoji1f551"></span> <span role="button" class="emoji emoji1f552"></span> <span role="button" class="emoji emoji1f553"></span> <span role="button" class="emoji emoji1f554"></span> <span role="button" class="emoji emoji1f555"></span> <span role="button" class="emoji emoji1f556"></span> <span role="button" class="emoji emoji1f557"></span> <span role="button" class="emoji emoji1f558"></span> <span role="button" class="emoji emoji1f559"></span> <span role="button" class="emoji emoji1f55a"></span> <span role="button" class="emoji emoji1f55b"></span> <span role="button" class="emoji emoji1f55c"></span> <span role="button" class="emoji emoji1f55d"></span> <span role="button" class="emoji emoji1f55e"></span> <span role="button" class="emoji emoji1f55f"></span> <span role="button" class="emoji emoji1f560"></span> <span role="button" class="emoji emoji1f561"></span> <span role="button" class="emoji emoji1f562"></span> <span role="button" class="emoji emoji1f563"></span> <span role="button" class="emoji emoji1f564"></span> <span role="button" class="emoji emoji1f565"></span> <span role="button" class="emoji emoji1f566"></span> <span role="button" class="emoji emoji1f567"></span> <span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span>'>
                        </div>
                        <!-- /.emojis -->
                    </div>
                    <!-- /.block -->
                    <script>
                        lister('symbols', 1);
                    </script>
                    <div id="flags" class="block wait">
                        <a class="tag-list pull-right" href="/emoji/list/flags/" title="lista">≡</a>
                        <h2>
                            <a href="/emoji/list/flags/#emoji-list">Bandeiras</a>
                        </h2>
                        <div class="emojis" data-cat="flags">
                            <span role="button" class="emoji emoji1f3f3"></span>
                            <input type='hidden' value='<span role="button" class="emoji emoji1f3f4"></span> <span role="button" class="emoji emoji1f3c1"></span> <span role="button" class="emoji emoji1f6a9"></span> <span role="button" class="emoji emoji1f38c"></span> <span role="button" class="emoji emoji1f3f4-200d-2620-fe0f"></span> <span role="button" class="emoji emoji1f3f3-fe0f-200d-1f308"></span> <span role="button" class="emoji emoji1f3f3-fe0f-200d-26a7-fe0f"></span> <span role="button" class="emoji emoji1f1e6-1f1e8"></span> <span role="button" class="emoji emoji1f1e6-1f1e9"></span> <span role="button" class="emoji emoji1f1e6-1f1ea"></span> <span role="button" class="emoji emoji1f1e6-1f1eb"></span> <span role="button" class="emoji emoji1f1e6-1f1ec"></span> <span role="button" class="emoji emoji1f1e6-1f1ee"></span> <span role="button" class="emoji emoji1f1e6-1f1f1"></span> <span role="button" class="emoji emoji1f1e6-1f1f2"></span> <span role="button" class="emoji emoji1f1e6-1f1f4"></span> <span role="button" class="emoji emoji1f1e6-1f1f6"></span> <span role="button" class="emoji emoji1f1e6-1f1f7"></span> <span role="button" class="emoji emoji1f1e6-1f1f8"></span> <span role="button" class="emoji emoji1f1e6-1f1f9"></span> <span role="button" class="emoji emoji1f1e6-1f1fa"></span> <span role="button" class="emoji emoji1f1e6-1f1fc"></span> <span role="button" class="emoji emoji1f1e6-1f1fd"></span> <span role="button" class="emoji emoji1f1e6-1f1ff"></span> <span role="button" class="emoji emoji1f1e7-1f1e6"></span> <span role="button" class="emoji emoji1f1e7-1f1e7"></span> <span role="button" class="emoji emoji1f1e7-1f1e9"></span> <span role="button" class="emoji emoji1f1e7-1f1ea"></span> <span role="button" class="emoji emoji1f1e7-1f1eb"></span> <span role="button" class="emoji emoji1f1e7-1f1ec"></span> <span role="button" class="emoji emoji1f1e7-1f1ed"></span> <span role="button" class="emoji emoji1f1e7-1f1ee"></span> <span role="button" class="emoji emoji1f1e7-1f1ef"></span> <span role="button" class="emoji emoji1f1e7-1f1f1"></span> <span role="button" class="emoji emoji1f1e7-1f1f2"></span> <span role="button" class="emoji emoji1f1e7-1f1f3"></span> <span role="button" class="emoji emoji1f1e7-1f1f4"></span> <span role="button" class="emoji emoji1f1e7-1f1f6"></span> <span role="button" class="emoji emoji1f1e7-1f1f7"></span> <span role="button" class="emoji emoji1f1e7-1f1f8"></span> <span role="button" class="emoji emoji1f1e7-1f1f9"></span> <span role="button" class="emoji emoji1f1e7-1f1fc"></span> <span role="button" class="emoji emoji1f1e7-1f1fe"></span> <span role="button" class="emoji emoji1f1e7-1f1ff"></span> <span role="button" class="emoji emoji1f1e8-1f1e6"></span> <span role="button" class="emoji emoji1f1e8-1f1e8"></span> <span role="button" class="emoji emoji1f1e8-1f1e9"></span> <span role="button" class="emoji emoji1f1e8-1f1eb"></span> <span role="button" class="emoji emoji1f1e8-1f1ec"></span> <span role="button" class="emoji emoji1f1e8-1f1ed"></span> <span role="button" class="emoji emoji1f1e8-1f1ee"></span> <span role="button" class="emoji emoji1f1e8-1f1f0"></span> <span role="button" class="emoji emoji1f1e8-1f1f1"></span> <span role="button" class="emoji emoji1f1e8-1f1f2"></span> <span role="button" class="emoji emoji1f1e8-1f1f3"></span> <span role="button" class="emoji emoji1f1e8-1f1f4"></span> <span role="button" class="emoji emoji1f1e8-1f1f7"></span> <span role="button" class="emoji emoji1f1e8-1f1fa"></span> <span role="button" class="emoji emoji1f1e8-1f1fb"></span> <span role="button" class="emoji emoji1f1e8-1f1fc"></span> <span role="button" class="emoji emoji1f1e8-1f1fd"></span> <span role="button" class="emoji emoji1f1e8-1f1fe"></span> <span role="button" class="emoji emoji1f1e8-1f1ff"></span> <span role="button" class="emoji emoji1f1e9-1f1ea"></span> <span role="button" class="emoji emoji1f1e9-1f1ef"></span> <span role="button" class="emoji emoji1f1e9-1f1f0"></span> <span role="button" class="emoji emoji1f1e9-1f1f2"></span> <span role="button" class="emoji emoji1f1e9-1f1f4"></span> <span role="button" class="emoji emoji1f1e9-1f1ff"></span> <span role="button" class="emoji emoji1f1ea-1f1e8"></span> <span role="button" class="emoji emoji1f3f4-e0067-e0062-e0065-e006e-e0067-e007f"></span> <span role="button" class="emoji emoji1f1ea-1f1ea"></span> <span role="button" class="emoji emoji1f1ea-1f1ec"></span> <span role="button" class="emoji emoji1f1ea-1f1ed"></span> <span role="button" class="emoji emoji1f1ea-1f1f7"></span> <span role="button" class="emoji emoji1f1ea-1f1f8"></span> <span role="button" class="emoji emoji1f1ea-1f1f9"></span> <span role="button" class="emoji emoji1f1ea-1f1fa"></span> <span role="button" class="emoji emoji1f1eb-1f1ee"></span> <span role="button" class="emoji emoji1f1eb-1f1ef"></span> <span role="button" class="emoji emoji1f1eb-1f1f0"></span> <span role="button" class="emoji emoji1f1eb-1f1f2"></span> <span role="button" class="emoji emoji1f1eb-1f1f4"></span> <span role="button" class="emoji emoji1f1eb-1f1f7"></span> <span role="button" class="emoji emoji1f1ec-1f1e6"></span> <span role="button" class="emoji emoji1f1ec-1f1e7"></span> <span role="button" class="emoji emoji1f1ec-1f1e9"></span> <span role="button" class="emoji emoji1f1ec-1f1ea"></span> <span role="button" class="emoji emoji1f1ec-1f1eb"></span> <span role="button" class="emoji emoji1f1ec-1f1ec"></span> <span role="button" class="emoji emoji1f1ec-1f1ed"></span> <span role="button" class="emoji emoji1f1ec-1f1ee"></span> <span role="button" class="emoji emoji1f1ec-1f1f1"></span> <span role="button" class="emoji emoji1f1ec-1f1f2"></span> <span role="button" class="emoji emoji1f1ec-1f1f3"></span> <span role="button" class="emoji emoji1f1ec-1f1f5"></span> <span role="button" class="emoji emoji1f1ec-1f1f6"></span> <span role="button" class="emoji emoji1f1ec-1f1f7"></span> <span role="button" class="emoji emoji1f1ec-1f1f8"></span> <span role="button" class="emoji emoji1f1ec-1f1f9"></span> <span role="button" class="emoji emoji1f1ec-1f1fa"></span> <span role="button" class="emoji emoji1f1ec-1f1fc"></span> <span role="button" class="emoji emoji1f1ec-1f1fe"></span> <span role="button" class="emoji emoji1f1ed-1f1f0"></span> <span role="button" class="emoji emoji1f1ed-1f1f3"></span> <span role="button" class="emoji emoji1f1ed-1f1f7"></span> <span role="button" class="emoji emoji1f1ed-1f1f9"></span> <span role="button" class="emoji emoji1f1ed-1f1fa"></span> <span role="button" class="emoji emoji1f1ee-1f1e8"></span> <span role="button" class="emoji emoji1f1ee-1f1e9"></span> <span role="button" class="emoji emoji1f1ee-1f1ea"></span> <span role="button" class="emoji emoji1f1ee-1f1f1"></span> <span role="button" class="emoji emoji1f1ee-1f1f2"></span> <span role="button" class="emoji emoji1f1ee-1f1f3"></span> <span role="button" class="emoji emoji1f1ee-1f1f4"></span> <span role="button" class="emoji emoji1f1ee-1f1f6"></span> <span role="button" class="emoji emoji1f1ee-1f1f7"></span> <span role="button" class="emoji emoji1f1ee-1f1f8"></span> <span role="button" class="emoji emoji1f1ee-1f1f9"></span> <span role="button" class="emoji emoji1f1ef-1f1ea"></span> <span role="button" class="emoji emoji1f1ef-1f1f2"></span> <span role="button" class="emoji emoji1f1ef-1f1f4"></span> <span role="button" class="emoji emoji1f1ef-1f1f5"></span> <span role="button" class="emoji emoji1f1f0-1f1ea"></span> <span role="button" class="emoji emoji1f1f0-1f1ec"></span> <span role="button" class="emoji emoji1f1f0-1f1ed"></span> <span role="button" class="emoji emoji1f1f0-1f1ee"></span> <span role="button" class="emoji emoji1f1f0-1f1f2"></span> <span role="button" class="emoji emoji1f1f0-1f1f3"></span> <span role="button" class="emoji emoji1f1f0-1f1f5"></span> <span role="button" class="emoji emoji1f1f0-1f1f7"></span> <span role="button" class="emoji emoji1f1f0-1f1fc"></span> <span role="button" class="emoji emoji1f1f0-1f1fe"></span> <span role="button" class="emoji emoji1f1f0-1f1ff"></span> <span role="button" class="emoji emoji1f1f1-1f1e6"></span> <span role="button" class="emoji emoji1f1f1-1f1e7"></span> <span role="button" class="emoji emoji1f1f1-1f1e8"></span> <span role="button" class="emoji emoji1f1f1-1f1ee"></span> <span role="button" class="emoji emoji1f1f1-1f1f0"></span> <span role="button" class="emoji emoji1f1f1-1f1f7"></span> <span role="button" class="emoji emoji1f1f1-1f1f8"></span> <span role="button" class="emoji emoji1f1f1-1f1f9"></span> <span role="button" class="emoji emoji1f1f1-1f1fa"></span> <span role="button" class="emoji emoji1f1f1-1f1fb"></span> <span role="button" class="emoji emoji1f1f1-1f1fe"></span> <span role="button" class="emoji emoji1f1f2-1f1e6"></span> <span role="button" class="emoji emoji1f1f2-1f1e8"></span> <span role="button" class="emoji emoji1f1f2-1f1e9"></span> <span role="button" class="emoji emoji1f1f2-1f1ea"></span> <span role="button" class="emoji emoji1f1f2-1f1ec"></span> <span role="button" class="emoji emoji1f1f2-1f1ed"></span> <span role="button" class="emoji emoji1f1f2-1f1f0"></span> <span role="button" class="emoji emoji1f1f2-1f1f1"></span> <span role="button" class="emoji emoji1f1f2-1f1f2"></span> <span role="button" class="emoji emoji1f1f2-1f1f3"></span> <span role="button" class="emoji emoji1f1f2-1f1f4"></span> <span role="button" class="emoji emoji1f1f2-1f1f5"></span> <span role="button" class="emoji emoji1f1f2-1f1f6"></span> <span role="button" class="emoji emoji1f1f2-1f1f7"></span> <span role="button" class="emoji emoji1f1f2-1f1f8"></span> <span role="button" class="emoji emoji1f1f2-1f1f9"></span> <span role="button" class="emoji emoji1f1f2-1f1fa"></span> <span role="button" class="emoji emoji1f1f2-1f1fb"></span> <span role="button" class="emoji emoji1f1f2-1f1fc"></span> <span role="button" class="emoji emoji1f1f2-1f1fd"></span> <span role="button" class="emoji emoji1f1f2-1f1fe"></span> <span role="button" class="emoji emoji1f1f2-1f1ff"></span> <span role="button" class="emoji emoji1f1f3-1f1e6"></span> <span role="button" class="emoji emoji1f1f3-1f1e8"></span> <span role="button" class="emoji emoji1f1f3-1f1ea"></span> <span role="button" class="emoji emoji1f1f3-1f1eb"></span> <span role="button" class="emoji emoji1f1f3-1f1ec"></span> <span role="button" class="emoji emoji1f1f3-1f1ee"></span> <span role="button" class="emoji emoji1f1f3-1f1f1"></span> <span role="button" class="emoji emoji1f1f3-1f1f4"></span> <span role="button" class="emoji emoji1f1f3-1f1f5"></span> <span role="button" class="emoji emoji1f1f3-1f1f7"></span> <span role="button" class="emoji emoji1f1f3-1f1fa"></span> <span role="button" class="emoji emoji1f1f3-1f1ff"></span> <span role="button" class="emoji emoji1f1f4-1f1f2"></span> <span role="button" class="emoji emoji1f1f5-1f1e6"></span> <span role="button" class="emoji emoji1f1f5-1f1ea"></span> <span role="button" class="emoji emoji1f1f5-1f1eb"></span> <span role="button" class="emoji emoji1f1f5-1f1ec"></span> <span role="button" class="emoji emoji1f1f5-1f1ed"></span> <span role="button" class="emoji emoji1f1f5-1f1f0"></span> <span role="button" class="emoji emoji1f1f5-1f1f1"></span> <span role="button" class="emoji emoji1f1f5-1f1f2"></span> <span role="button" class="emoji emoji1f1f5-1f1f3"></span> <span role="button" class="emoji emoji1f1f5-1f1f7"></span> <span role="button" class="emoji emoji1f1f5-1f1f8"></span> <span role="button" class="emoji emoji1f1f5-1f1f9"></span> <span role="button" class="emoji emoji1f1f5-1f1fc"></span> <span role="button" class="emoji emoji1f1f5-1f1fe"></span> <span role="button" class="emoji emoji1f1f6-1f1e6"></span> <span role="button" class="emoji emoji1f1f7-1f1ea"></span> <span role="button" class="emoji emoji1f1f7-1f1f4"></span> <span role="button" class="emoji emoji1f1f7-1f1f8"></span> <span role="button" class="emoji emoji1f1f7-1f1fa"></span> <span role="button" class="emoji emoji1f1f7-1f1fc"></span> <span role="button" class="emoji emoji1f1f8-1f1e6"></span> <span role="button" class="emoji emoji1f3f4-e0067-e0062-e0073-e0063-e0074-e007f"></span> <span role="button" class="emoji emoji1f1f8-1f1e7"></span> <span role="button" class="emoji emoji1f1f8-1f1e8"></span> <span role="button" class="emoji emoji1f1f8-1f1e9"></span> <span role="button" class="emoji emoji1f1f8-1f1ea"></span> <span role="button" class="emoji emoji1f1f8-1f1ec"></span> <span role="button" class="emoji emoji1f1f8-1f1ed"></span> <span role="button" class="emoji emoji1f1f8-1f1ee"></span> <span role="button" class="emoji emoji1f1f8-1f1f0"></span> <span role="button" class="emoji emoji1f1f8-1f1f1"></span> <span role="button" class="emoji emoji1f1f8-1f1f2"></span> <span role="button" class="emoji emoji1f1f8-1f1f3"></span> <span role="button" class="emoji emoji1f1f8-1f1f4"></span> <span role="button" class="emoji emoji1f1f8-1f1f7"></span> <span role="button" class="emoji emoji1f1f8-1f1f8"></span> <span role="button" class="emoji emoji1f1f8-1f1f9"></span> <span role="button" class="emoji emoji1f1f8-1f1fb"></span> <span role="button" class="emoji emoji1f1f8-1f1fd"></span> <span role="button" class="emoji emoji1f1f8-1f1fe"></span> <span role="button" class="emoji emoji1f1f8-1f1ff"></span> <span role="button" class="emoji emoji1f1f9-1f1e6"></span> <span role="button" class="emoji emoji1f1f9-1f1e8"></span> <span role="button" class="emoji emoji1f1f9-1f1e9"></span> <span role="button" class="emoji emoji1f1f9-1f1eb"></span> <span role="button" class="emoji emoji1f1f9-1f1ec"></span> <span role="button" class="emoji emoji1f1f9-1f1ed"></span> <span role="button" class="emoji emoji1f1f9-1f1ef"></span> <span role="button" class="emoji emoji1f1f9-1f1f0"></span> <span role="button" class="emoji emoji1f1f9-1f1f1"></span> <span role="button" class="emoji emoji1f1f9-1f1f2"></span> <span role="button" class="emoji emoji1f1f9-1f1f3"></span> <span role="button" class="emoji emoji1f1f9-1f1f4"></span> <span role="button" class="emoji emoji1f1f9-1f1f7"></span> <span role="button" class="emoji emoji1f1f9-1f1f9"></span> <span role="button" class="emoji emoji1f1f9-1f1fb"></span> <span role="button" class="emoji emoji1f1f9-1f1fc"></span> <span role="button" class="emoji emoji1f1f9-1f1ff"></span> <span role="button" class="emoji emoji1f1fa-1f1e6"></span> <span role="button" class="emoji emoji1f1fa-1f1ec"></span> <span role="button" class="emoji emoji1f1fa-1f1f3"></span> <span role="button" class="emoji emoji1f1fa-1f1f8"></span> <span role="button" class="emoji emoji1f1fa-1f1fe"></span> <span role="button" class="emoji emoji1f1fa-1f1ff"></span> <span role="button" class="emoji emoji1f1fb-1f1e6"></span> <span role="button" class="emoji emoji1f1fb-1f1e8"></span> <span role="button" class="emoji emoji1f1fb-1f1ea"></span> <span role="button" class="emoji emoji1f1fb-1f1ec"></span> <span role="button" class="emoji emoji1f1fb-1f1ee"></span> <span role="button" class="emoji emoji1f1fb-1f1f3"></span> <span role="button" class="emoji emoji1f1fb-1f1fa"></span> <span role="button" class="emoji emoji1f3f4-e0067-e0062-e0077-e006c-e0073-e007f"></span> <span role="button" class="emoji emoji1f1fc-1f1eb"></span> <span role="button" class="emoji emoji1f1fc-1f1f8"></span> <span role="button" class="emoji emoji1f1fd-1f1f0"></span> <span role="button" class="emoji emoji1f1fe-1f1ea"></span> <span role="button" class="emoji emoji1f1fe-1f1f9"></span> <span role="button" class="emoji emoji1f1ff-1f1e6"></span> <span role="button" class="emoji emoji1f1ff-1f1f2"></span> <span role="button" class="emoji emoji1f1ff-1f1fc"></span> <span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span><span class="dummy"></span>'>
                        </div>
                        <!-- /.emojis -->
                    </div>
                    <!-- /.block -->
                    <script>
                        lister('flags', 1);
                    </script>
                    <a name="tag"></a>
                    <div id="dfp-3" class='ads ads-728x90 idx-3' style='width:728px;height:90px'>
                        <script>
                            googletag.cmd.push(function() {
                                googletag.display('dfp-3');
                            });
                        </script>
                    </div>
                    <div id="tags" class="block wait2">
                        <h2>Conteúdos relacionados</h2>
                        <input type="hidden" value='<ul class="nav nav-pills">
<li class="active"><a href="/emoji/list/angry/"><b class="emoji emoji1f620"></b> emoji zangado</a></li><li class="active"><a href="/emoji/list/animals/"><b class="emoji emoji1f992"></b> animais emoji</a></li><li class="active"><a href="/emoji/list/apple/"><b class="emoji emoji1f34e"></b> emoji de maçã</a></li><li class="active"><a href="/emoji/list/arrow/"><b class="emoji emoji2b06"></b> seta emoji</a></li><li class="active"><a href="/emoji/list/birthday/"><b class="emoji emoji1f382"></b> emoji de aniversário</a></li><li class="active"><a href="/emoji/list/black/"><b class="emoji emoji2b1b"></b> emoji preto</a></li><li class="active"><a href="/emoji/list/blue/"><b class="emoji emoji1f7e6"></b> emoji azul</a></li><li class="active"><a href="/emoji/list/book/"><b class="emoji emoji1f4d6"></b> livro emoji</a></li><li class="active"><a href="/emoji/list/bullet-point/"><b class="emoji emoji25aa"></b> ponto de bala</a></li><li class="active"><a href="/emoji/list/camera/"><b class="emoji emoji1f4f8"></b> Emoji da câmera</a></li><li class="active"><a href="/emoji/list/car/"><b class="emoji emoji1f3ce"></b> carro emoji</a></li><li class="active"><a href="/emoji/list/cat/"><b class="emoji emoji1f63a"></b> gato emoji</a></li><li class="active"><a href="/emoji/list/check-mark/"><b class="emoji emoji2705"></b> Emoji de marca de seleção</a></li><li class="active"><a href="/emoji/list/christmas/"><b class="emoji emoji1f385"></b> emoji de natal</a></li><li class="active"><a href="/emoji/list/circle/"><b class="emoji emoji2b55"></b> emoji de círculo</a></li><li class="active"><a href="/emoji/list/constellation/"><b class="emoji emoji2648"></b> constelação emoji</a></li><li class="active"><a href="/emoji/list/cool/"><b class="emoji emoji1f60e"></b> emoji legal</a></li><li class="active"><a href="/emoji/list/crown/"><b class="emoji emoji1f451"></b> coroa emoji</a></li><li class="active"><a href="/emoji/list/crying/"><b class="emoji emoji1f622"></b> chorando emoji</a></li><li class="active"><a href="/emoji/list/dog/"><b class="emoji emoji1f436"></b> emoji de cachorro</a></li><li class="active"><a href="/emoji/list/eye/"><b class="emoji emoji1f441"></b> olho emoji</a></li><li class="active"><a href="/emoji/list/fire/"><b class="emoji emoji1f525"></b> emoji de fogo</a></li><li class="active"><a href="/emoji/list/flower/"><b class="emoji emoji1f339"></b> emoji de flor</a></li><li class="active"><a href="/emoji/list/game/"><b class="emoji emoji1f3ae"></b> emoji de jogo</a></li><li class="active"><a href="/emoji/list/girl/"><b class="emoji emoji1f467"></b> menina emoji</a></li><li class="active"><a href="/emoji/list/good/"><b class="emoji emoji1f44d"></b> bom emoji</a></li><li class="active"><a href="/emoji/list/green/"><b class="emoji emoji1f7e9"></b> emoji verde</a></li><li class="active"><a href="/emoji/list/hand/"><b class="emoji emoji270c"></b> Mão emoji</a></li><li class="active"><a href="/emoji/list/happy/"><b class="emoji emoji1f600"></b> Emoji feliz</a></li><li class="active"><a href="/emoji/list/hazard/"><b class="emoji emoji26a0"></b> símbolos de perigo</a></li><li class="active"><a href="/emoji/list/heart/"><b class="emoji emoji2764"></b> Emoji coração</a></li><li class="active"><a href="/emoji/list/hot/"><b class="emoji emoji1f975"></b> emoji quente</a></li><li class="active"><a href="/emoji/list/hug/"><b class="emoji emoji1f917"></b> abraço emoji</a></li><li class="active"><a href="/emoji/list/japan/"><b class="emoji emoji1f1ef-1f1f5"></b> cultura japonesa emoji</a></li><li class="active"><a href="/emoji/list/kiss/"><b class="emoji emoji1f48b"></b> beijo emoji</a></li><li class="active"><a href="/emoji/list/laughing/"><b class="emoji emoji1f606"></b> emoji rindo</a></li><li class="active"><a href="/emoji/list/lgbt/"><b class="emoji emoji1f308"></b> Emoji LGBT</a></li><li class="active"><a href="/emoji/list/mail/"><b class="emoji emoji2709"></b> correio emoji</a></li><li class="active"><a href="/emoji/list/middle-finger/"><b class="emoji emoji1f595"></b> Emoji do dedo médio</a></li><li class="active"><a href="/emoji/list/money/"><b class="emoji emoji1f4b0"></b> dinheiro emoji</a></li><li class="active"><a href="/emoji/list/monkey/"><b class="emoji emoji1f435"></b> macaco emoji</a></li><li class="active"><a href="/emoji/list/moon/"><b class="emoji emoji1f319"></b> lua emoji</a></li><li class="active"><a href="/emoji/list/movie/"><b class="emoji emoji1f3a6"></b> emoji de filme</a></li><li class="active"><a href="/emoji/list/music/"><b class="emoji emoji1f3b5"></b> música emoji</a></li><li class="active"><a href="/emoji/list/number/"><b class="emoji emoji1f522"></b> número emoji</a></li><li class="active"><a href="/emoji/list/party/"><b class="emoji emoji1f973"></b> festa emoji</a></li><li class="active"><a href="/emoji/list/peace/"><b class="emoji emoji262e"></b> emoji da paz</a></li><li class="active"><a href="/emoji/list/phone/"><b class="emoji emoji260e"></b> emoji de telefone</a></li><li class="active"><a href="/emoji/list/pink-heart/"><b class="emoji emoji1f496"></b> coração rosa</a></li><li class="active"><a href="/emoji/list/pink/"><b class="emoji emoji1f493"></b> emoji rosa</a></li><li class="active"><a href="/emoji/list/playing-cards/"><b class="emoji emoji2663"></b> baralhos de cartas</a></li><li class="active"><a href="/emoji/list/purple/"><b class="emoji emoji1f7ea"></b> emoji roxo</a></li><li class="active"><a href="/emoji/list/red/"><b class="emoji emoji1f7e5"></b> emoji vermelho</a></li><li class="active"><a href="/emoji/list/sad/"><b class="emoji emoji1f61e"></b> triste emoji</a></li><li class="active"><a href="/emoji/list/scared/"><b class="emoji emoji1f631"></b> emoji assustado</a></li><li class="active"><a href="/emoji/list/scissors/"><b class="emoji emoji2702"></b> tesoura emoji</a></li><li class="active"><a href="/emoji/list/shrug/"><b class="emoji emoji1f937-200d-2640-fe0f"></b> encolher os ombros emoji</a></li><li class="active"><a href="/emoji/list/sick/"><b class="emoji emoji1f637"></b> emoji doente</a></li><li class="active"><a href="/emoji/list/sleeping/"><b class="emoji emoji1f62a"></b> dormindo emoji</a></li><li class="active"><a href="/emoji/list/sparkle/"><b class="emoji emoji2728"></b> emoji brilhante</a></li><li class="active"><a href="/emoji/list/star/"><b class="emoji emoji2b50"></b> Emoji de símbolo de estrela</a></li><li class="active"><a href="/emoji/list/sun/"><b class="emoji emoji1f31e"></b> sol emoji</a></li><li class="active"><a href="/emoji/list/thinking/"><b class="emoji emoji1f914"></b> Pensando emoji</a></li><li class="active"><a href="/emoji/list/thumbs-up/"><b class="emoji emoji1f44d"></b> polegares para cima emoji</a></li><li class="active"><a href="/emoji/list/time/"><b class="emoji emoji1f570"></b> emoji de tempo</a></li><li class="active"><a href="/emoji/list/virus/"><b class="emoji emoji1f9a0"></b> vírus emoji</a></li><li class="active"><a href="/emoji/list/water/"><b class="emoji emoji1f4a7"></b> emoji de água</a></li><li class="active"><a href="/emoji/list/weather/"><b class="emoji emoji1f324"></b> emoji do tempo</a></li><li class="active"><a href="/emoji/list/white/"><b class="emoji emoji2b1c"></b> emoji branco</a></li><li class="active"><a href="/emoji/list/x-mark/"><b class="emoji emoji274c"></b> x marca emoji</a></li><li class="active"><a href="/emoji/list/yellow/"><b class="emoji emoji1f7e8"></b> emoji amarelo</a></li></ul>
'>
                        <style>
                            #tags .emoji1f620 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f620.png);
                            }

                            #tags .emoji1f992 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f992.png);
                            }

                            #tags .emoji1f34e {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f34e.png);
                            }

                            #tags .emoji2b06 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/2b06.png);
                            }

                            #tags .emoji1f382 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f382.png);
                            }

                            #tags .emoji2b1b {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/2b1b.png);
                            }

                            #tags .emoji1f7e6 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f7e6.png);
                            }

                            #tags .emoji1f4d6 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f4d6.png);
                            }

                            #tags .emoji25aa {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/25aa.png);
                            }

                            #tags .emoji1f4f8 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f4f8.png);
                            }

                            #tags .emoji1f3ce {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f3ce.png);
                            }

                            #tags .emoji1f63a {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f63a.png);
                            }

                            #tags .emoji2705 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/2705.png);
                            }

                            #tags .emoji1f385 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f385.png);
                            }

                            #tags .emoji2b55 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/2b55.png);
                            }

                            #tags .emoji2648 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/2648.png);
                            }

                            #tags .emoji1f60e {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f60e.png);
                            }

                            #tags .emoji1f451 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f451.png);
                            }

                            #tags .emoji1f622 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f622.png);
                            }

                            #tags .emoji1f436 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f436.png);
                            }

                            #tags .emoji1f441 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f441.png);
                            }

                            #tags .emoji1f525 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f525.png);
                            }

                            #tags .emoji1f339 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f339.png);
                            }

                            #tags .emoji1f3ae {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f3ae.png);
                            }

                            #tags .emoji1f467 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f467.png);
                            }

                            #tags .emoji1f44d {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f44d.png);
                            }

                            #tags .emoji1f7e9 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f7e9.png);
                            }

                            #tags .emoji270c {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/270c.png);
                            }

                            #tags .emoji1f600 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f600.png);
                            }

                            #tags .emoji26a0 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/26a0.png);
                            }

                            #tags .emoji2764 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/2764.png);
                            }

                            #tags .emoji1f975 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f975.png);
                            }

                            #tags .emoji1f917 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f917.png);
                            }

                            #tags .emoji1f1ef-1f1f5 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f1ef-1f1f5.png);
                            }

                            #tags .emoji1f48b {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f48b.png);
                            }

                            #tags .emoji1f606 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f606.png);
                            }

                            #tags .emoji1f308 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f308.png);
                            }

                            #tags .emoji2709 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/2709.png);
                            }

                            #tags .emoji1f595 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f595.png);
                            }

                            #tags .emoji1f4b0 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f4b0.png);
                            }

                            #tags .emoji1f435 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f435.png);
                            }

                            #tags .emoji1f319 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f319.png);
                            }

                            #tags .emoji1f3a6 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f3a6.png);
                            }

                            #tags .emoji1f3b5 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f3b5.png);
                            }

                            #tags .emoji1f522 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f522.png);
                            }

                            #tags .emoji1f973 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f973.png);
                            }

                            #tags .emoji262e {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/262e.png);
                            }

                            #tags .emoji260e {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/260e.png);
                            }

                            #tags .emoji1f496 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f496.png);
                            }

                            #tags .emoji1f493 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f493.png);
                            }

                            #tags .emoji2663 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/2663.png);
                            }

                            #tags .emoji1f7ea {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f7ea.png);
                            }

                            #tags .emoji1f7e5 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f7e5.png);
                            }

                            #tags .emoji1f61e {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f61e.png);
                            }

                            #tags .emoji1f631 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f631.png);
                            }

                            #tags .emoji2702 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/2702.png);
                            }

                            #tags .emoji1f937-200d-2640-fe0f {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f937-200d-2640-fe0f.png);
                            }

                            #tags .emoji1f637 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f637.png);
                            }

                            #tags .emoji1f62a {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f62a.png);
                            }

                            #tags .emoji2728 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/2728.png);
                            }

                            #tags .emoji2b50 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/2b50.png);
                            }

                            #tags .emoji1f31e {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f31e.png);
                            }

                            #tags .emoji1f914 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f914.png);
                            }

                            #tags .emoji1f44d {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f44d.png);
                            }

                            #tags .emoji1f570 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f570.png);
                            }

                            #tags .emoji1f9a0 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f9a0.png);
                            }

                            #tags .emoji1f4a7 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f4a7.png);
                            }

                            #tags .emoji1f324 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f324.png);
                            }

                            #tags .emoji2b1c {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/2b1c.png);
                            }

                            #tags .emoji274c {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/274c.png);
                            }

                            #tags .emoji1f7e8 {
                                background-image: url(https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.0/72x72/1f7e8.png);
                            }
                        </style>
                    </div>
                    <div class="footer">
                        <button class="btn btn-small" id="erase-all" data-confirm="Limpar todos os dados?">Limpar todos os dados</button>
                        <style type="text/css">
                            .base-footer div {
                                text-align: center;
                                margin: .5em auto
                            }

                            @media only screen and (max-width: 575px) {
                                .base-footer div {
                                    display:inline
                                }

                                .base-footer div:last-child:before {
                                    content: " | "
                                }
                            }

                            .base-footer a {
                                height: 1rem;
                                display: inline-block
                            }

                            #languages.win7 {
                                background: url(//cdnjs.cloudflare.com/ajax/libs/twemoji/12.0.4/2/svg/1f310.svg) no-repeat;
                                background-size: 1em;
                                display: inline-block;
                                width: 1em;
                                height: 1em;
                                line-height: 1em;
                                text-indent: -999em;
                                overflow: hidden
                            }
                        </style>
                        <div class="base-footer">
                            <div>
                                <a href="https://pt.piliapp.com">Início</a>
                                | 
<a href="/label/symbols/">Emoji e símbolos</a>
                                | <a href="/label/text/">Ferramenta de texto</a>
                                | <a href="/label/time-and-date/">Data e Hora</a>
                                | <a href="/label/utilities/">Utilitários</a>
                            </div>
                            <div>
                                <a rel="nofollow" href="/feedback/report/" target="_blank">Informar um problema</a>
                                | <a href="/lnk/*http://global-blog.piliapp.com">Blog</a>
                                | <a href="/page/privacy/">Privacidade</a>
                                | <a href="/page/terms/">Termos</a>
                                | <a id="languages" href="/page/language/?app_uri=%2Femoji%2Flist%2F" rel="nofollow">🌐</a>
                                | © 2023
                            </div>
                            <div>
                                ᴅᴇsɪɢɴᴇᴅ ʙʏ
 <a style="font-variant:small-caps;opacity:.7;" href="https://pili.app">pili.app</a>
                                <span id="footer-from">ɪɴ ᴛᴀɪᴡᴀɴ</span>
                                <span id="footer-thx"></span>
                                <script type="text/javascript">
                                    !function() {
                                        var o = navigator.language || ""
                                          , t = location.host.split(".")[0]
                                          , e = (("; " + document.cookie).match(/; loc=(\w+)/) || [0, ""])[1]
                                          , t = "cn" == t || o.match(/(zh-CN|zh-Hans)/) || e.match(/(CN)/)
                                          , o = document.querySelector("#footer-from");
                                        t && o.parentNode.removeChild(o)
                                    }();
                                </script>
                            </div>
                        </div>
                        <script type="text/javascript">
                            0 < navigator.userAgent.indexOf("Windows NT 6.1") && document.querySelector("#languages").classList.add("win7");
                        </script>
                    </div>
                </div>
                <!-- /.content -->
                <div class="side-ads">
                    <div id="twins">
                        <style>
                            @media (min-width: 0px) {
                                .ads-auto.idx-0 {
                                    display:none;
                                }
                            }

                            @media (min-width: 1080px) {
                                .ads-auto.idx-0 {
                                    display:block;
                                    width: 120px;
                                    height: 600px;
                                }
                            }

                            @media (min-width: 1260px) {
                                .ads-auto.idx-0 {
                                    display:block;
                                    width: 300px;
                                    height: 250px;
                                }
                            }

                            .ads-auto.idx-0.hide {
                                display: none;
                            }
                        </style>
                        <div id="dfp-4" class='ads ads-auto idx-0' style=''>
                            <script>
                                googletag.cmd.push(function() {
                                    googletag.display('dfp-4');
                                });
                            </script>
                        </div>
                        <style>
                            @media (min-width: 0px) {
                                .ads-auto.idx-1 {
                                    display:none;
                                }
                            }

                            @media (min-width: 1260px) {
                                .ads-auto.idx-1 {
                                    display:block;
                                    width: 300px;
                                    height: 250px;
                                }
                            }

                            .ads-auto.idx-1.hide {
                                display: none;
                            }
                        </style>
                        <div id="dfp-5" class='ads ads-auto idx-1' style='margin-top:10px;'>
                            <script>
                                googletag.cmd.push(function() {
                                    googletag.display('dfp-5');
                                });
                            </script>
                        </div>
                    </div>
                    <style>
                        @media (min-width: 0px) {
                            .ads-auto.idx-2 {
                                display:none;
                            }
                        }

                        @media (min-width: 1080px) {
                            .ads-auto.idx-2 {
                                display:block;
                                width: 120px;
                                height: 600px;
                            }
                        }

                        @media (min-width: 1260px) {
                            .ads-auto.idx-2 {
                                display:block;
                                width: 300px;
                                height: 600px;
                            }
                        }

                        .ads-auto.idx-2.hide {
                            display: none;
                        }
                    </style>
                    <div id="dfp-6" class='ads ads-auto idx-2' style=''>
                        <script>
                            googletag.cmd.push(function() {
                                googletag.display('dfp-6');
                            });
                        </script>
                    </div>
                </div>
                <script>
                    document.querySelector(".side-ads").style.minHeight = (document.querySelector(".content").offsetHeight - 30) + 'px';
                </script>
            </div>
            <!-- /.row -->
        </div>
        <!-- /.container -->
        <script>
            var APP_URI = "/emoji/list/"
              , APP_NAME = "emoji-list"
              , preview_off = (navigator.userAgent.indexOf('MSIE 8') !== -1)
              , LOADING_GIF = "//cdnjs.cloudflare.com/ajax/libs/timelinejs/2.36.0/css/blank.gif"
              , XHR_DESC_PATH = '//assets.piliapp.com/xhr/pt/emojis/xhr-get-desc/14.0.0.js?v=202303' + (location.protocol == 'http:' ? '&ssl=0' : '')
              , I18N = {
                icon_copied: "{1} foi copiado",
                icon_insert: "Clique no \u00edcone para inserir s\u00edmbolo para textarea.",
                text_copied: "O texto foi copiado para a \u00e1rea de transfer\u00eancia",
                paste: "Pasta",
                copy_alert: "Este smartphone n\u00e3o pode executar a fun\u00e7\u00e3o de c\u00f3pia. Por favor, copie manualmente, obrigado.",
                touch_to_copy: "imprensa e \u00edcone de espera para selecionar, clique em Copiar",
                reset_confirm: "Voc\u00ea tem certeza?"
            };

            preview_off = true;
        </script>
        <script src="//pt.piliapp.com/assets/v3/13kl9_7gcht.js"></script>
        <script>
            window.Promise || document.write(unescape("%3Cscript%20src%3D%22%2F%2Fcdnjs.cloudflare.com%2Fajax%2Flibs%2Fes6-promise%2F4.1.1%2Fes6-promise.auto.min.js%22%3E%3C%2Fscript%3E"));
        </script>
        <script src="//pt.piliapp.com/assets/v3/ap4wz_264ow.js"></script>
    </body>
</html>
