# SmartDamperDemo
		<p>
		This demo is an Angular + Angular UI Bootstrap + ng-table rewrite that
		simulates control of a collection of HVAC dampers found on a building's 10th floor.
		Clicking on a damper drills down to that damper and allows the user to adjust the CFM for the selected damper.
		A quick click on the Floor Controller link gets back to the previous floor view that shows the CFM change.
		</p><p>
		Data for each damper was collected via an Ajax echo call. ng-table allows for ascending/descendingsortable
		sortable columns, paginated tables. Angular mouse hover events over a damper changes their color. 
		ng-routing used to handle partial view loads (also provides design/development simplicity)
		<p>
