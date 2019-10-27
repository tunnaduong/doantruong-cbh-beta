---
layout: home
home: active
---
<div class='containerbg'>
<h2><strong class='sep-onenbt'></strong>Cổng thông tin điện tử Đoàn trường<strong class='sep-twonbt'></strong></h2>
<h2>THPT Chuyên Biên Hoà</h2>
</div>
<div class='containerbg sma' style="
    padding-top: 24px;
    margin-top: 125px;
">
<big><b><i class="fas fa-question-circle"></i> Đây là gì?</b></big>
<p>Chào mừng đến với cổng thông tin điện tử Đoàn trường Chuyên Biên Hoà! Đây là nơi để tra cứu các thông tin, vấn đề liên quan đến xung kích của Đoàn trường THPT Chuyên Biên Hoà.</p>
<br>
<big><b><i class="fas fa-bolt"></i> Bạn có thể làm được gì với website này?</b></big>
<p>- Tra cứu các lỗi vi phạm trong tuần của lớp
<br>- Tra cứu xếp hạng tháng
<br>- Biết được những sự kiện, hoạt động mới nhất của Đoàn trường THPT Chuyên Biên Hoà
<br>- Có thể đóng góp ý kiến, phản hồi của mình trực tiếp với xung kích hoặc thầy cô giáo
<br>Và nhiều hơn thế... Hãy tự mình khám phá nhé!
</p>
<br>
<big><b><i class="far fa-address-book"></i> Liên hệ với Đoàn trường</b></big>
<p></p>
<button type="button" style="
    padding-top: 6px;
    margin-top: 10px;
" class="btn btn-info" onclick="location.href='https://www.facebook.com/Đoàn-Trường-THPT-Chuyên-Biên-Hòa-1318791134932333/';">
   <i class="fab fa-facebook-square"></i>
Facebook</button>
<button type="button" style="
    padding-top: 6px;
    margin-top: 10px;
" class="btn btn-info" onclick="location.href='mailto:hoaiduong281983@gmail.com';">
   <i class="fas fa-envelope"></i>
Email</button>
</div>
<nav class='navbar navbar-inverse '>
<div class='container-fluid'>
<div class='navbar-header'>
<a class='navbar-brand' href='https://tunganh03.github.io/doantruong-cbh/'>Đoàn trường - CBH</a>
<button class='navbar-toggle' data-target='#myNavbar' data-toggle='collapse' type='button'>
<span class='icon-bar'></span>
<span class='icon-bar'></span>
<span class='icon-bar'></span>
</button>
</div>
<div class='collapse navbar-collapse' id='myNavbar'>
<ul class='nav navbar-nav'>
<li class='{{ page.home }}'><a href='https://tunganh03.github.io/doantruong-cbh/'>Trang chủ</a></li>
<li class='{{ page.tc }}'><a href='/tracuu'>Tra cứu</a></li>
<li class='{{ page.tvp }}'><a href='/topvipham'>Top vi phạm</a></li>
<li class='{{ page.hdsk }}'><a href='/hoatdong'>Hoạt động/Sự kiện</a></li>
<li class='{{ page.bc }}'><a href='/baocao'>Báo cáo</a></li>
<li class='{{ page.lh }}'><a href='/lienhe'>Liên hệ</a></li>
</ul> 
<ul class='nav navbar-nav navbar-right flex-row justify-content-between ml-auto'>
<li class="dropdown order-1">
                    <button type="button" id="dropdownMenu1" data-toggle="dropdown" class="btn btn-outline-secondary dropdown-toggle" style="
    margin-top: 8px;
"><i class="fas fa-sign-in-alt"></i> Đăng nhập <span class="caret"></span></button>
                    <ul class="dropdown-menu dropdown-menu-right mt-2">
                       <li class="px-3 py-2" style="
    height: 196px;
    width: 240px;
    padding-top: 15px;
    padding-right: 15px;
    padding-left: 15px;
">
   <form class="form" role="form">
                                <div class="form-group">
                                    <input id="emailInput" placeholder="Email" class="form-control form-control-sm" type="text" required="">
                                </div>
                                <div class="form-group">
                                    <input id="passwordInput" placeholder="Mật khẩu" class="form-control form-control-sm" type="text" required="">
                                </div>
                                <div class="form-group">
                                    <button type="submit" class="btn btn-primary btn-block">Đăng nhập</button>
                                </div>
                                <div class="form-group text-center">
                                    <small><a href="#" data-toggle="modal" data-target="#modalPassword">Quên mật khẩu?</a></small>
                                </div>
                            </form>
                        </li>
                    </ul>
                </li>
</ul>
</div>
</div>
</nav>

<div id="modalPassword" class="modal fade" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <h3>Quên mật khẩu</h3>
                <button type="button" class="close font-weight-light" data-dismiss="modal" style="
    padding-bottom: 0px;
    margin-top: 0px;
    margin-bottom: 1px;
    height: 1px;
    border-bottom-width: 0px;
    width: 17px;
" aria-hidden="true">×</button>
            </div>
            <div class="modal-body">
                <p>Reset mật khẩu..</p>
            </div>
            <div class="modal-footer">
                <button class="btn" data-dismiss="modal" aria-hidden="true">Đóng</button>
                <button class="btn btn-primary">Lưu thay đổi</button>
            </div>
        </div>
<div id="modalSignup" class="modal fade" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <h3>Đăng ký</h3>
                <button type="button" class="close font-weight-light" data-dismiss="modal" style="
    padding-bottom: 0px;
    margin-top: 0px;
    margin-bottom: 1px;
    height: 1px;
    border-bottom-width: 0px;
    width: 17px;
" aria-hidden="true">×</button>
            </div>
            <div class="modal-body">
                <p>Tên đăng nhập..</p>
            </div>
            <div class="modal-footer">
                <button class="btn" data-dismiss="modal" aria-hidden="true">Đóng</button>
                <button class="btn btn-primary">Đăng ký</button>
            </div>
        </div>
<div id='wrappernbt'>
<div class='contentabove'>
<div id='headernbt'>
<p>Hello World</p>
</div>
<div id='middlenbt'>
<p>Hello World</p>
</div>
<div id='footernbt'>
<p>Hello World</p>
</div>
<div class='no-items section' id='fixelements'></div>

<script type="text/javascript" src="https://www.blogger.com/static/v1/widgets/2136525808-widgets.js"></script>
<script type='text/javascript'>
window['__wavt'] = 'AOuZoY4AuX9rsJ2Gp_rRU0ZMTlbMC7eCWw:1571650462951';_WidgetManager._Init('//www.blogger.com/rearrange?blogID\x3d8152930394054794091','//c4k60.blogspot.com/','8152930394054794091');
_WidgetManager._SetDataContext([{'name': 'blog', 'data': {'blogId': '8152930394054794091', 'title': 'C4K60', 'url': 'https://c4k60.blogspot.com/', 'canonicalUrl': 'https://c4k60.blogspot.com/', 'homepageUrl': 'https://c4k60.blogspot.com/', 'searchUrl': 'https://c4k60.blogspot.com/search', 'canonicalHomepageUrl': 'https://c4k60.blogspot.com/', 'blogspotFaviconUrl': 'https://c4k60.blogspot.com/favicon.ico', 'bloggerUrl': 'https://www.blogger.com', 'hasCustomDomain': false, 'httpsEnabled': true, 'enabledCommentProfileImages': true, 'gPlusViewType': 'FILTERED_POSTMOD', 'adultContent': false, 'analyticsAccountNumber': '', 'encoding': 'UTF-8', 'locale': 'vi', 'localeUnderscoreDelimited': 'vi', 'languageDirection': 'ltr', 'isPrivate': false, 'isMobile': false, 'isMobileRequest': false, 'mobileClass': '', 'isPrivateBlog': false, 'feedLinks': '\x3clink rel\x3d\x22alternate\x22 type\x3d\x22application/atom+xml\x22 title\x3d\x22C4K60 - Atom\x22 href\x3d\x22https://c4k60.blogspot.com/feeds/posts/default\x22 /\x3e\n\x3clink rel\x3d\x22alternate\x22 type\x3d\x22application/rss+xml\x22 title\x3d\x22C4K60 - RSS\x22 href\x3d\x22https://c4k60.blogspot.com/feeds/posts/default?alt\x3drss\x22 /\x3e\n\x3clink rel\x3d\x22service.post\x22 type\x3d\x22application/atom+xml\x22 title\x3d\x22C4K60 - Atom\x22 href\x3d\x22https://www.blogger.com/feeds/8152930394054794091/posts/default\x22 /\x3e\n', 'meTag': '\x3clink rel\x3d\x22me\x22 href\x3d\x22https://www.blogger.com/profile/02354055521114731558\x22 /\x3e\n', 'adsenseHostId': 'ca-host-pub-1556223355139109', 'adsenseHasAds': false, 'view': '', 'dynamicViewsCommentsSrc': '//www.blogblog.com/dynamicviews/4224c15c4e7c9321/js/comments.js', 'dynamicViewsScriptSrc': '//www.blogblog.com/dynamicviews/f78c150ef2198f1c', 'plusOneApiSrc': 'https://apis.google.com/js/plusone.js', 'disableGComments': true, 'sharing': {'platforms': [{'name': 'Nhận liên kết', 'key': 'link', 'shareMessage': 'Nhận liên kết', 'target': ''}, {'name': 'Facebook', 'key': 'facebook', 'shareMessage': 'Chia sẻ với Facebook', 'target': 'facebook'}, {'name': 'BlogThis!', 'key': 'blogThis', 'shareMessage': 'BlogThis!', 'target': 'blog'}, {'name': 'Twitter', 'key': 'twitter', 'shareMessage': 'Chia sẻ với Twitter', 'target': 'twitter'}, {'name': 'Pinterest', 'key': 'pinterest', 'shareMessage': 'Chia sẻ với Pinterest', 'target': 'pinterest'}, {'name': 'Email', 'key': 'email', 'shareMessage': 'Email', 'target': 'email'}], 'disableGooglePlus': true, 'googlePlusShareButtonWidth': 300, 'googlePlusBootstrap': '\x3cscript type\x3d\x22text/javascript\x22\x3ewindow.___gcfg \x3d {\x27lang\x27: \x27vi\x27};\x3c/script\x3e'}, 'hasCustomJumpLinkMessage': false, 'jumpLinkMessage': 'Đọc thêm', 'pageType': 'index', 'pageName': '', 'pageTitle': 'C4K60'}}, {'name': 'features', 'data': {'sharing_get_link_dialog': 'true', 'sharing_native': 'false'}}, {'name': 'messages', 'data': {'edit': 'Chỉnh sửa', 'linkCopiedToClipboard': 'Đã sao chép liên kết vào khay nhớ tạm!', 'ok': 'Ok', 'postLink': 'Liên kết bài đăng'}}, {'name': 'template', 'data': {'name': 'custom', 'localizedName': 'Tùy chỉnh', 'isResponsive': false, 'isAlternateRendering': false, 'isCustom': true}}, {'name': 'view', 'data': {'classic': {'name': 'classic', 'url': '?view\x3dclassic'}, 'flipcard': {'name': 'flipcard', 'url': '?view\x3dflipcard'}, 'magazine': {'name': 'magazine', 'url': '?view\x3dmagazine'}, 'mosaic': {'name': 'mosaic', 'url': '?view\x3dmosaic'}, 'sidebar': {'name': 'sidebar', 'url': '?view\x3dsidebar'}, 'snapshot': {'name': 'snapshot', 'url': '?view\x3dsnapshot'}, 'timeslide': {'name': 'timeslide', 'url': '?view\x3dtimeslide'}, 'isMobile': false, 'title': 'C4K60', 'description': 'Chuyên Nga THPT Chuyên Biên Hoà', 'url': 'https://c4k60.blogspot.com/', 'type': 'feed', 'isSingleItem': false, 'isMultipleItems': true, 'isError': false, 'isPage': false, 'isPost': false, 'isHomepage': true, 'isArchive': false, 'isLabelSearch': false}}]);
</script>
</body>
</html>
