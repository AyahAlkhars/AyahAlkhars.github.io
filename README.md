# AyahAlkhars.github.io
My data journalism work 

<head>
	<title>Abortion regulations by state - Washington Post</title>

	<style>

	/*desktop*/
		
		/*FONTS*/

		@font-face {
			font-family:"Franklin Bold";
			src:url(fonts/ITCFranklinGothicStd-Med.otf);
		}

		@font-face {
			font-family:"Franklin Light";
			src:url(fonts/franklin-gothic-light.ttf);
		}

		/*UNIVERSAL PAGE STYLES*/

		body {
			margin:40px;
			color:#2a2a2a;
		}

		h1 {
			font-family: "Franklin Bold", Helvetica, Arial, sans-serif;
			font-size: 1.8em;
			font-weight:800;
		}

		p {
			font-family:"Franklin Light", Helvetica, Arial, sans-serif;
			font-size:1.1em;
			line-height:1.3em;
			word-spacing:-1px;
			font-weight:100;
		}

		/*TOP BOX STYLES*/

		.top {
			padding-top:30px;
			border-top:1.5px solid #D5D5D5;
		}

		.left{
			float:left;
			width:40%;
		}
		.right{float:left;
		width:55%;
		margin-left:5%;
		 }

		.callout {
			font-family:"Franklin Bold",Helvetica, Arial, sans-serif;
			font-weight:800;
		}

		.highlight1 {
			background-color:RGBA(196,176,199,.5);
			padding:5px;
			border-radius:3px;
		}

		.highlight2 {
			background-color:RGBA(169,189,176,.5);
			padding:5px;
			border-radius:3px;
		}

		/*MIDDLE BOX STYLES*/

		.middle {
			text-align:center;
			clear:both;
		}


.story-link {

			font-family:Georgia, serif; 
			font-style:italic;
			color:#2e6d9d
			
		}



		/*BOTTOM BOX STYLES*/

		.bottom {
			clear:both;
			margin-top:50px;
			border-top:1.5px solid #D5D5D5;		
			padding-top:30px;
		}

		.map-wrap {

			float:left;
			width:19%;
			margin-right:1%
			text-align:center;



		}

		.mapwrap p {
			font-size: 1em
			margin-top: -1px;
			line-height: 1.3em;

		}

		.total {

			font-family: "franklin Bold", Helvetica, arial, sans-serif;
			font-size: 1.5em

		}

		.bottom-chart{

		width:100%;
		clear:both;
		text-align: center;
		}

		.bottom-chart img {
			max-width: 420px
		}

		.bottom-source {
			color:#969696;
			line-height: 20px;
			float:left;
			font-size: .8em;
			border-bottom: 1px solid#D5D5D5;
			padding-bottom: 5px
			margin-bottom: 20px;
		}
/*Tablet*/

	@media (max-width: 800px) {

		body{
			margin: 10px;
		}

		.left {
			width:100%;
			float: none;
		}

		.right {
			width:100%;
			float: none;
			margin-left: 0%;
		}

		.map-wrap {
			width:30%;
			margin-right: 3%;}
		}

		.clear {
			clear:both;
		}
	

@media (max-width: 480px) {

	.map-wrap {
		width:90%;
		padding: 0% 5%;
	}

	.map-wrap img {
		display: none;
	}

	.bottom-chart img {
		width:90%;
	}
}


	</style>

</head>
<body>
	<div class="top">
		<div class="left">
			<h1>A closer look at five regulations</h1>
			<p>There are <span class="callout">31 states</span> that have at least one of the following abortion regulations: waiting periods, restrictions on health insurance coverage, bans after 20 weeks of pregnancy, requirements that clinics <span class="highlight1">meet ambulatory surgical center standards</span> or requirements that <span class="highlight2">abortion doctors have hospital admitting privileges</span>. Regulations for clinics to meet ambulatory surgical center standards vary by state, and some are more restrictive than others.</p>
			<p>There are <span class="callout">25 states</span>, not including Texas, that have at least one of the last two regulations, which were covered in the Supreme Court ruling on June 27. That does not include Kansas, which has been temporarily enjoined from both ambulatory surgical center standards and requiring hospital privileges. Alabama, Louisiana, Mississippi, and Wisconsin have been temporarily enjoined from requiring hospital privileges. Oklahoma has been permanently enjoined from requiring hospital privileges.</p>
		</div>
		<div class="right">
			<img src="img/top-map-1.svg"></img>
		</div>
	</div>
	<div class="middle">
		<p class="link">[
			<a class="story-link" href="https://www.washingtonpost.com/news/to-your-health/wp/2016/06/27/the-supreme-court-rules-against-texas-and-for-science-in-abortion-case/?utm_term=.43194c3fcc93">Supreme Court rules against Texas and for science in abortion case</a>
			]
		</p>
	</div>
	<div class="bottom">
		<div class="bottom-maps">
			<div class="map-wrap">
				<img src="img/bottom-map-1.svg"></img>
				<span class="total" style="color: #835B89">24 states*</span>
				<p>require abortion clinics to meet standards similar to those for ambulatory surgical centers</p>
			</div>
			<div class="map-wrap">
				<img src="img/bottom-map-2.svg"></img>
				<span class="total" style="color:#6F917B"; >4 states*</span>
				<p>require abortion doctors to have admitting privileges at local hospitals</p>
			</div>
			<div class="map-wrap">
				<img src="img/bottom-map-3.svg"></img>
				<span class="total" style="color: #BBA135">27 states</span>
				<p>have waiting periods</p>
			</div>

<!--this is a clear!-->
			<div class="clear"></div>
	
			<div class="map-wrap">
				<img src="img/bottom-map-4.svg"></img>
				<span class="total" style="color:#AF7852;"">10 states</span>
				<p>restrict health insurance coverage for abortions</p>
			</div>

			<div class="map-wrap">
				<img src="img/bottom-map-5.svg"></img>
				<span class="total" style="color:#6796B0;" >17 states</span>
				<p>ban abortion at about 20 weeks postfertilization</p>
			</div>
		</div>

		<div class="bottom-chart">
			<img src="img/bottom-chart-1.svg"></img>
		</div>

		<div class="bottom-source">
			<p>Source: Guttmacher Institute. *Note: Kansas and Texas have requirements for abortion clinics to meet ambulatory surgical center standards. These requirements are on hold while they are under review by federal courts. Some states may also have requirements that are temporarily enjoined for other regulations.</p>
		</div>
	</div>	
</body>









