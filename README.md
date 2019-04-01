# JavaScript-day-date-month-year
showing date in JavaScript

# Example 1:

								<script type = "text/javascript" >
									var dayNames = new Array("Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday");

									// Array of month Names
									var monthNames = new Array(
										"January", "February", "March", "April", "May", "June", "July",
										"August", "September", "October", "November", "December");


									var now = new Date();
									var dayOfTheWeek = now.getDay();
									now.setTime(now.getTime() - 0 * 24 * 60 * 60 * 1000);

									document.write(dayNames[(now.getDay())] + ", " + monthNames[(now.getMonth())] + " " + now.getDate() + ", " + now.getFullYear()) // returns new calculated date
								</script>
