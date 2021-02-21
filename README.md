# TIC TAC TOE

Before launching add java-FX library:
- First choose item: File > Project Structure... > Libraries
- Then click "+" button
- From dropdown list choose Java
- Then select lib folder from java-FX library. For example: `/home/Teacher/dev/javafx-sdk-11.0.2/lib`

Then create run configuration. You can try run `TicTacToe.java` and it appeared automatically.
Choose run configuration for TicTacToe (Run > Edit Configuration) and add to VM options:

--module-path /home/Teacher/dev/javafx-sdk-11.0.2/lib --add-modules javafx.controls,javafx.fxml

Where `/home/Teacher/dev/javafx-sdk-11.0.2/lib` is path to Java-FX lib folder.