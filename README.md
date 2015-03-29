# Bootstrap iPod Style jQuery Drill Down Menu Plugin

![Screenshot](bootstrap.drilldown.png)

##Demos

**[Live demo on bootply](http://www.bootply.com/hIuKeY1K4t)**

**[Live demo app on mewsoft.com](http://mewsoft.com/app/)**

##Full Example Code

```
<!DOCTYPE html>
<html>
	<head>
		<title>Bootstrap iPod Style jQuery Drill Down Menu Plugin</title>
		<meta charset="utf-8">
		<meta http-equiv="X-UA-Compatible" content="IE=edge">
		<meta name="viewport" content="width=device-width, initial-scale=1">
		<!-- link href="css/dcdrilldown.css" rel="stylesheet" type="text/css" /-->
		<link rel="stylesheet" href="http://netdna.bootstrapcdn.com/bootstrap/3.3.4/css/bootstrap.min.css" />
		<link rel="stylesheet" href="http://netdna.bootstrapcdn.com/bootstrap/3.3.4/css/bootstrap-theme.min.css" />
		<link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css" />
		<!--[if lt IE 9]>
		<script src="https://oss.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script>
		<script src="https://oss.maxcdn.com/libs/respond.js/1.4.2/respond.min.js"></script>
		<![endif]-->
		<script src="http://code.jquery.com/jquery.min.js"></script>
		<script type="text/javascript" src="jquery.cookie.js"></script>
		<script src="http://netdna.bootstrapcdn.com/bootstrap/3.3.4/js/bootstrap.min.js"></script>
		
		<link rel="stylesheet" href="bootstrap.drilldown.css" />
        <script type="text/javascript" src="bootstrap.drilldown.js"></script>

	</head>

	<body>
		<div class="container">
			<div class="row">
				<div class="col-sm-8">
					<br><br>
					<div class="">
						<ul id="drilldown">
							<li><a href="#">Home</a></li>
							<li>
								<a href="#">Products</a>
								<ul>
									<li>
										<a href="#">Mobile Phones &#038; Accessories</a>
										<ul>
											<li>
												<a href="#">Product 1</a>
												<ul>
													<li>
														<a href="#">Part A</a>
														<ul>
															<li>
																<a href="#">Sale</a>
																<ul>
																	<li>
																		<a href="#">Special Offers</a>
																		<ul>
																			<li><a href="#">Offer 1</a></li>
																			<li><a href="#">Offer 2</a></li>
																			<li><a href="#">Offer 3</a></li>
																		</ul>
																	</li>
																	<li>
																		<a href="#">Reduced Price</a>
																		<ul>
																			<li><a href="#">Offer 4</a></li>
																			<li><a href="#">Offer 5</a></li>
																			<li><a href="#">Offer 6</a></li>
																			<li><a href="#">Offer 7</a></li>
																		</ul>
																	</li>
																	<li>
																		<a href="#">Clearance Items</a>
																		<ul>
																			<li><a href="#">Offer 9</a></li>
																		</ul>
																	</li>
																	<li class="menu-item-129">
																		<a href="#">Ex-Stock</a>
																		<ul>
																			<li><a href="#">Offer 10</a></li>
																			<li><a href="#">Offer 11</a></li>
																			<li><a href="#">Offer 12</a></li>
																			<li><a href="#">Offer 13</a></li>
																		</ul>
																	</li>
																</ul>
															</li>
														</ul>
													</li>
													<li><a href="#">Part B</a></li>
													<li><a href="#">Part C</a></li>
													<li><a href="#">Part D</a></li>
												</ul>
											</li>
											<li>
												<a href="#">Product 2</a
													>
												<ul>
													<li><a href="#">Part A</a></li>
													<li><a href="#">Part B</a></li>
													<li><a href="#">Part C</a></li>
													<li><a href="#">Part D</a></li>
												</ul>
											</li>
											<li>
												<a href="#">Product 3</a>
												<ul>
													<li><a href="#">Part A</a></li>
													<li><a href="#">Part B</a></li>
													<li><a href="#">Part C</a></li>
													<li><a href="#">Part D</a></li>
												</ul>
											</li>
										</ul>
									</li>
									<li>
										<a href="#">Desktop</a>
										<ul>
											<li>
												<a href="#">Product 4</a>
												<ul>
													<li><a href="#">Part E</a></li>
													<li><a href="#">Part F</a></li>
													<li><a href="#">Part G</a></li>
													<li><a href="#">Part H</a></li>
												</ul>
											</li>
											<li>
												<a href="#">Product 5</a>
												<ul>
													<li><a href="#">Part E</a></li>
													<li><a href="#">Part E</a></li>
													<li><a href="#">Part F</a></li>
													<li><a href="#">Part G</a></li>
													<li><a href="#">Part H</a></li>
													<li><a href="#">Part G</a></li>
													<li><a href="#">Part H</a></li>
												</ul>
											</li>
											<li>
												<a href="#">Product 6</a>
												<ul>
													<li><a href="#">Part E</a></li>
													<li><a href="#">Part F</a></li>
													<li><a href="#">Part G</a></li>
													<li><a href="#">Part H</a></li>
												</ul>
											</li>
											<li>
												<a href="#">Product 7</a>
												<ul>
													<li><a href="#">Part E</a></li>
													<li><a href="#">Part F</a></li>
													<li><a href="#">Part G</a></li>
													<li><a href="#">Part H</a></li>
												</ul>
											</li>
											<li>
												<a href="#">Product 8</a>
												<ul>
													<li><a href="#">Part E</a></li>
													<li><a href="#">Part F</a></li>
													<li><a href="#">Part G</a></li>
													<li><a href="#">Part H</a></li>
												</ul>
											</li>
											<li>
												<a href="#">Product 9</a>
												<ul>
													<li><a href="#">Part E</a></li>
													<li><a href="#">Part F</a></li>
													<li><a href="#">Part G</a></li>
													<li><a href="#">Part H</a></li>
												</ul>
											</li>
										</ul>
									</li>
									<li>
										<a href="#">Laptop</a>
										<ul>
											<li><a href="#">Product 10</a></li>
											<li>
												<a href="#">Product 11</a>
												<ul>
													<li><a href="#">Part E</a></li>
													<li><a href="#">Part F</a></li>
													<li><a href="#">Part G</a></li>
													<li><a href="#">Part H</a></li>
												</ul>
											</li>
											<li><a href="#">Product 12</a></li>
											<li><a href="#">Product 13</a></li>
										</ul>
									</li>
									<li>
										<a href="#">Accessories</a>
										<ul>
											<li><a href="#">Product 14</a></li>
											<li><a href="#">Product 15</a></li>
										</ul>
									</li>
									<li>
										<a href="#">Software</a>
										<ul>
											<li><a href="#">Product 16</a></li>
											<li><a href="#">Product 17</a></li>
											<li><a href="#">Product 18</a></li>
											<li><a href="#">Product 19</a></li>
										</ul>
									</li>
								</ul>
							</li>
							<li>
								<a href="#">Services</a>
								<ul>
									<li>
										<a href="#">Mobile Phones &#038; Accessories</a>
										<ul>
											<li>
												<a href="#">Product 1</a>
												<ul>
													<li>
														<a href="#">Part A</a>
														<ul>
															<li>
																<a href="#">Sale</a>
																<ul>
																	<li>
																		<a href="#">Special Offers</a>
																		<ul>
																			<li><a href="#">Offer 1</a></li>
																			<li><a href="#" class="selected">Offer 2</a></li>
																			<li><a href="#">Offer 3</a></li>
																		</ul>
																	</li>
																	<li>
																		<a href="#">Reduced Price</a>
																		<ul>
																			<li><a href="#">Offer 4</a></li>
																			<li><a href="#">Offer 5</a></li>
																			<li><a href="#">Offer 6</a></li>
																			<li><a href="#">Offer 7</a></li>
																		</ul>
																	</li>
																	<li>
																		<a href="#">Clearance Items</a>
																		<ul>
																			<li><a href="#">Offer 9</a></li>
																		</ul>
																	</li>
																	<li class="menu-item-129">
																		<a href="#">Ex-Stock</a>
																		<ul>
																			<li><a href="#">Offer 10</a></li>
																			<li><a href="#">Offer 11</a></li>
																			<li><a href="#">Offer 12</a></li>
																			<li><a href="#">Offer 13</a></li>
																		</ul>
																	</li>
																</ul>
															</li>
														</ul>
													</li>
													<li><a href="#">Part B</a></li>
													<li><a href="#">Part C</a></li>
													<li><a href="#">Part D</a></li>
												</ul>
											</li>
											<li>
												<a href="#">Product 2</a
													>
												<ul>
													<li><a href="#">Part A</a></li>
													<li><a href="#">Part B</a></li>
													<li><a href="#">Part C</a></li>
													<li><a href="#">Part D</a></li>
												</ul>
											</li>
											<li>
												<a href="#">Product 3</a>
												<ul>
													<li><a href="#">Part A</a></li>
													<li><a href="#">Part B</a></li>
													<li><a href="#">Part C</a></li>
													<li><a href="#">Part D</a></li>
												</ul>
											</li>
										</ul>
									</li>
									<li>
										<a href="#">Desktop</a>
										<ul>
											<li>
												<a href="#">Product 4</a>
												<ul>
													<li><a href="#">Part E</a></li>
													<li><a href="#">Part F</a></li>
													<li><a href="#">Part G</a></li>
													<li><a href="#">Part H</a></li>
												</ul>
											</li>
											<li>
												<a href="#">Product 5</a>
												<ul>
													<li><a href="#">Part E</a></li>
													<li><a href="#">Part E</a></li>
													<li><a href="#">Part F</a></li>
													<li><a href="#">Part G</a></li>
													<li><a href="#">Part H</a></li>
													<li><a href="#">Part G</a></li>
													<li><a href="#">Part H</a></li>
												</ul>
											</li>
											<li>
												<a href="#">Product 6</a>
												<ul>
													<li><a href="#">Part E</a></li>
													<li><a href="#">Part F</a></li>
													<li><a href="#">Part G</a></li>
													<li><a href="#">Part H</a></li>
												</ul>
											</li>
											<li>
												<a href="#">Product 7</a>
												<ul>
													<li><a href="#">Part E</a></li>
													<li><a href="#">Part F</a></li>
													<li><a href="#">Part G</a></li>
													<li><a href="#">Part H</a></li>
												</ul>
											</li>
											<li>
												<a href="#">Product 8</a>
												<ul>
													<li><a href="#">Part E</a></li>
													<li><a href="#">Part F</a></li>
													<li><a href="#">Part G</a></li>
													<li><a href="#">Part H</a></li>
												</ul>
											</li>
											<li>
												<a href="#">Product 9</a>
												<ul>
													<li><a href="#">Part E</a></li>
													<li><a href="#">Part F</a></li>
													<li><a href="#">Part G</a></li>
													<li><a href="#">Part H</a></li>
												</ul>
											</li>
										</ul>
									</li>
									<li>
										<a href="#">Laptop</a>
										<ul>
											<li><a href="#">Product 10</a></li>
											<li>
												<a href="#">Product 11</a>
												<ul>
													<li><a href="#">Part E</a></li>
													<li><a href="#">Part F</a></li>
													<li><a href="#">Part G</a></li>
													<li><a href="#">Part H</a></li>
												</ul>
											</li>
											<li><a href="#">Product 12</a></li>
											<li><a href="#">Product 13</a></li>
										</ul>
									</li>
									<li>
										<a href="#">Accessories</a>
										<ul>
											<li><a href="#">Product 14</a></li>
											<li><a href="#">Product 15</a></li>
										</ul>
									</li>
									<li>
										<a href="#">Software</a>
										<ul>
											<li><a href="#">Product 16</a></li>
											<li><a href="#">Product 17</a></li>
											<li><a href="#">Product 18</a></li>
											<li><a href="#">Product 19</a></li>
										</ul>
									</li>
								</ul>
							</li>
						</ul>
					</div>
				</div>
				<div class="clearfix"></div>
			</div>
		</div>

		<script type="text/javascript">
			$(document).ready(function($){
			
				$('#drilldown').drilldown({
			                 wrapper_class	    : 'drilldown panel panel-success',
			                 menu_class		    : 'drilldown-menu',
			                 submenu_class	    : 'nav ',
			                 parent_class		: 'dd-parent',
			                 parent_class_link	: 'dd-parent-a',
			                 active_class		: 'active',
			                 header_class_list  : 'breadcrumb',
			                 header_class		: 'breadcrumbwrapper',
			                 class_selected     : 'selected',
			                 event_type		    : 'click',
			                 hover_delay	    : 300,
			                 speed       	    : 'fast',
			                 save_state		    : true,
			                 show_count		    : false,
			                 count_class	    : 'dd-count',
			                 icon_class		    : 'fa fa-chevron-right pull-right dd-icon',
			                 link_type		    : 'breadcrumb', //breadcrumb , link, backlink
			                 reset_text		    : '<span class="fa fa-folder-open"></span>', // All
			                 default_text	    : 'Select Category',
			                 show_end_nodes     : true, // drill to final empty nodes
			                 hide_empty         : true, // hide empty menu when menu_height is set, header no effected
			                 menu_height        : '200px', // '200px' , false for auto height
			                 show_header	    : false,
			                 header_tag		    : 'div',// h3
			                 header_tag_class   : 'list-group-item active' // hidden list-group-item active
				});
			
                 $('#drilldown').on('click', function(e){
                     console.log('click');
                 });
    
                 $('#drilldown').on('drilldown.parentclick', function(e){
                     console.log('drilldown.parentclick');
                 });
                 $('#drilldown').on('drilldown.linklclick', function(e){
                     console.log('drilldown.linklclick');
                 });
			});
		</script>

	</body>
</html>

```

## Author

**Dr. Ahmed Amin Elsheshtawy, Ph.D.**

+ [http://github.com/mewsoft](http://github.com/mewsoft)
+ [http://mewsoft.com/](http://mewsoft.com/)
