# ui Draggable function:

1. appendTo => $( ".selector" ).draggable({
appendTo: "body"
});

2. axis =>  $( ".selector" ).draggable({
axis: "x"
});

3. cursor => $( ".selector" ).draggable({
cursor: "crosshair" / "move", cursorAt: { top: 56, left: 56 }
});

4. cursorAt => $( ".selector" ).draggable({
cursorAt: { left: 5 }
});

5. delay => $( ".selector" ).draggable({
delay: 300
});

6. handle =>  $( ".selector" ).draggable({
handle: "h2"
});

7. helper => $( ".selector" ).draggable({
helper: "clone"
});

8. opacity => $( ".selector" ).draggable({
opacity: 0.35
});

9. refreshPositions => $( ".selector" ).draggable({
refreshPositions: true
});

10. revert =>  $( ".selector" ).draggable({
revert: true
});

11. revertDuration => $( ".selector" ).draggable({
revertDuration: 200
});

12. zIndex => $( ".selector" ).draggable({
zIndex: 100
});

13. destroy => $( ".selector" ).draggable( "destroy" );

14. disable => $( ".selector" ).draggable( "disable" );

15. enable => $( ".selector" ).draggable( "enable" );

16. create( event, ui ) => $( ".selector" ).draggable({
create: function( event, ui ) {}
});

17. drag( event, ui ) => $( ".selector" ).draggable({
drag: function( event, ui ) {}
});

18. start( event, ui ) => $( ".selector" ).draggable({
start: function( event, ui ) {}
});

19. stop( event, ui ) => $( ".selector" ).draggable({
stop: function( event, ui ) {}
});

20. containment => $( ".selector" ).draggable({
  containment: "parent"/"special Id"
});

# ui Droppable function:
Controls which draggable elements are accepted by the droppable.

1. accept => $( ".selector" ).droppable({
  accept: ".special"
});

2. activeClass =>  $( ".selector" ).droppable({
  activeClass: "ui-state-highlight"
});

3. addClasses => $( ".selector" ).droppable({
  addClasses: false
});

4. hoverClass => $( ".selector" ).droppable({
  hoverClass: "drop-hover"
});

5. droppable => $( ".selector" ).droppable( "destroy" );

6. droppable => $( ".selector" ).droppable( "enable" );


7. drop( event, ui ) => $( ".selector" ).droppable({
  drop: function( event, ui ) {}
});

8. create( event, ui ) => $( ".selector" ).droppable({
  create: function( event, ui ) {}
});

# Resizable :

class="ui-widget-content" => class add in resizable id.

1. resizable =>  $( "#resizable" ).resizable();

2. alsoResize => $( ".selector" ).resizable({
  alsoResize: "#mirror"
});

3. animate => $( ".selector" ).resizable({
  animate: true
});

4. animateDuration=>  $( ".selector" ).resizable({
  animateDuration: "fast"
});

5. animateEasing => $( ".selector" ).resizable({
  animateEasing: "easeOutBounce"
});

6. aspectRatio => $( ".selector" ).resizable({
  aspectRatio: true
});

7. autoHide =>  $( ".selector" ).resizable({
  autoHide: true
});

8. cancel=> $( ".selector" ).resizable({
  cancel: ".cancel"
});

9. containment => $( ".selector" ).resizable({
  containment: "parent"
});

10. delay => $( ".selector" ).resizable({
  delay: 150
});

11. disabled => $( ".selector" ).resizable({
  disabled: true
});

12. distance => $( ".selector" ).resizable({
  distance: 30
});

13. ghost => $( ".selector" ).resizable({
  ghost: true
});

14. grid => $( ".selector" ).resizable({
  grid: [ 20, 10 ]
});

15. handles => $( ".selector" ).resizable({
  handles: "n, e, s, w"
});

16. helper => $( ".selector" ).resizable({
  helper: "resizable-helper"
});

17. minimam and maximam => $( ".selector" ).resizable({
  maxHeight: 300,maxWidth: 300
});

18. minimam and maximam => $( ".selector" ).resizable({
  minHeight: 150,minWidth: 150
});

19. destroy => $( ".selector" ).resizable( "destroy" );

20. disable => $( ".selector" ).resizable( "disable" );

21. enable => $( ".selector" ).resizable( "enable" );

22. instance => $( ".selector" ).resizable( "instance" );

23. create( event, ui ) => $( ".selector" ).resizable({
  create: function( event, ui ) {}
});

24. resize( event, ui ) => $( ".selector" ).resizable({
  resize: function( event, ui ) {}
});

25. start( event, ui ) => $( ".selector" ).resizable({
  start: function( event, ui ) {}
});

26. stop( event, ui ) => $( ".selector" ).resizable({
  stop: function( event, ui ) {}
});

# ui Accordion :

1. accordion =>  $( "#accordion" ).accordion();

2. collapsible => $( "#accordion" ).accordion({
  collapsible: true
});

3. heightStyle=>  $( "#accordion" ).accordion({
  heightStyle: "fill"
});

4. refresh => $( "#accordion" ).accordion( "refresh" );

5.

6.

7.

8.

9.

10.
