# prg1jfx

```
        Label nameLbl= new Label("Name:");
        nameLbl.setPrefWidth(40);
        TextField nameTxt= new TextField();
        nameTxt.setPrefWidth(100);
        Label ageLbl= new Label("Alter:");
        nameLbl.setPrefWidth(40);
        TextField ageTxt= new TextField();
        ageTxt.setPrefWidth(20);
        Button btn = new Button("OK");

        FlowPane pane = new FlowPane(10,10, nameLbl, nameTxt, ageLbl, ageTxt, btn);
        Scene scene = new Scene(pane, 300 , 400);
        stage.setTitle("Hello!");
        stage.setScene(scene);
        stage.show();       
```
