# ui Draggable function:

1. appendTo => $( ".selector" ).draggable({
appendTo: "body"
});

2. axis =>  $( ".selector" ).draggable({
axis: "x"
});

3. cursor => $( ".selector" ).draggable({
cursor: "crosshair"
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


