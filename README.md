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

1. resizable =>  $( "#resizable" ).resizable();

















