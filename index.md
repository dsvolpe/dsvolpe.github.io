---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: Daniel Serrano - Professional Site
layout: single
author_profile: true
---
<div id="adobe-dc-view" style="width: 800px;"></div>
<script src="https://documentcloud.adobe.com/view-sdk/main.js"></script>
<script type="text/javascript">
	document.addEventListener("adobe_dc_view_sdk.ready", function(){ 
		var adobeDCView = new AdobeDC.View({clientId: "115a140da1ad40ffaebe8981794def8d", divId: "adobe-dc-view"});
		adobeDCView.previewFile({
			content:{location: {url: "https://dsvolpe.github.io/assets/images/serrano_ShortCVJan2022.pdf"}},
			metaData:{fileName: "serrano_ShortCVJan2022.pdf"}
		}, {embedMode: "IN_LINE"});
	});
</script>
