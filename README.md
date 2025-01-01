<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
		<meta
			name="viewport"
			content="width=device-width, initial-scale=1.0, user-scalable=no"
		/>
		<title>个人生活记录分享</title>
		<link
			rel="stylesheet"
			href="js/global.css"
		/>
		<link
			rel="stylesheet"
			href="js/stop-page.css"
		/>
	</head>

	<body>
		<div class="body">
			<div class="stop-page">
				<div class="sp-fir">
					<div class="sp-w sp-noaccess">
						<div class="spa-logo">
							<img
								src="js/Stop-page.svg"
								alt=""
							/>
						</div>
						<div class="spa-text">
							<div class="spa-tit">个人生活记录分享</div>
							<div class="spa-desc">
							一个风景也许会勾起美好的回忆
							</div>
						</div>
					</div>
				</div>
				<div class="sp-sec ">
					<div class="sp-w sp-if">
						<div class="if-common">
							<div class="ifc">
								<div class="ifc-tit">人总有那么一段美好的回忆，路过的风景匆匆而过为何不挽留</div>
								<div class="ifc-desc">大自然的美好，也让无数的人留连忘返，无数的风景又牵动着无数人的心，在今天这个网络快拍的时代已经没有太多的人来记忆和回忆一些美好的事情，对此小编以个人站点的形式来给予大家展示风景图片，愿一切美好！但是很抱歉小编能力有限，目前程序一直在完善当中。</div>
							</div>
						</div>
						<div class="if-slice"></div>
						
					</div>
				</div>
			</div>
			<div class="stop-footer">
				<p class="sf-num"><a href="http://beian.miit.gov.cn" target="_blank">豫ICP备2024046820号-2</a></p>
			</div>
		</div>
		<script
			id="sdi_js"
			aid="2019103118575411963"
			type="text/javascript"
			src="js/sdi_js_full_v2.js"
		></script>
		<script>
			document.querySelectorAll("a").forEach(el => {
				el.addEventListener("click", e => {
					try {
						let tag = e.currentTarget.dataset.sdi;
						let psArr = tag.split("-");
						let ptype = psArr[0];
						let stype = psArr[1];
						_sdi.stat({
							ptype: ptype,
							stype: stype
						});
					} catch (error) {}
				});
			});
		</script>
	</body>
</html>
<!--[if !IE]>|xGv00|8f85bc5ee2a463e0e5c16c474a6dd271<![endif]-->
