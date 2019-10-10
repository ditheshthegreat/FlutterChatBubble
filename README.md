# FlutterChatBubble
Hey i have just created a chat bubble Widget in flutter using custom paint.

Copy and paste the ChatBubble.dart file in your project and paste this code where you have to show chatBubble Widget


```
Align(
      alignment: alignment, //Change this to Alignment.topRight or Alignment.topLeft
      child: CustomPaint(
        painter: ChatBubble(color: Colors.blue, alignment: alignment),
        child: Container(
          margin: EdgeInsets.all(10),
          child: Stack(
            children: <Widget>[
              TextView("Hello World"),
            ],
          ),
        ),
      ),
    )
