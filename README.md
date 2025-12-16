# prg1jfx

```
        Label nameLbl= new Label("Name:");
        nameLbl.setPrefWidth(50);
        TextField nameTxt= new TextField();
        nameTxt.setPrefWidth(150);
        HBox nameBox= new HBox(5,nameLbl,nameTxt);

        Button btn = new Button("I am a button");
        VBox componentGroup = new VBox();
        componentGroup.setSpacing(20);
        componentGroup.getChildren().add(nameBox);
        componentGroup.getChildren().add(btn);


        Scene scene = new Scene(componentGroup, 320, 240);
        stage.setTitle("Hello!");
        stage.setScene(scene);
        stage.show();
```
