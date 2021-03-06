# Using the Tools in the Amazon Sumerian Editor<a name="editor-tools"></a>

The Amazon Sumerian editor provides three tool panels for working with complex assets and components\. The text editor provides an interface for authoring scripts, JSON documents, and speech files\. The timeline editor animates entities between keyframes, and the state machine editor lets you visually construct and connect state machine behaviors and actions\.

## Text Editor<a name="editor-tools-texteditor"></a>

The text editor lets you view and modify all text assets in the scene, including scripts, JSON documents, and speech files\.

![\[Image NOT FOUND\]](http://docs.aws.amazon.com/sumerian/latest/userguide/images/tools-texteditor.png)

To use the text editor, choose **Tools**, **Text Editor**, or press the J key\.

The **Documents** panel lists the text assets in your seen\. Click on one to open it in a tab\. To rename an asset, highlight it and click the pencil icon\.

When you open a script, the **External Resources** panel appears\. You can use this panel to import libraries that your script depends on from the Internet\. See [External Dependencies](scripting-dependencies.md) for more information\.

## State Machine Editor<a name="editor-tools-statemachine"></a>

The state machine editor provides a visual representation of the actions and behaviors attached to a state machine component\.

![\[Image NOT FOUND\]](http://docs.aws.amazon.com/sumerian/latest/userguide/images/tools-statemachine.png)

To use the state machine editor, click the pencil icon next to a behavior in the assets panel or on a state machine component\.

The state machine editor shows a box for each behavior, each with a stack of actions listed in the order that they execute\. When an action transitions to another behavior, an arrow connects the action to the target behavior\. Click on an action and drag the cursor to a behavior to create a transition between the two\.

## Timeline<a name="editor-tools-timeline"></a>

Use timelines to move, rotate, or change the scale of entities over time\. You can set the start and end values of these properties, and add keyframes to control the speed or direction of the animation along the way\. The timeline can also emit custom events, which can be consumed from a state machine or script\.

![\[Image NOT FOUND\]](http://docs.aws.amazon.com/sumerian/latest/userguide/images/tools-timeline.png)

For more information, see [The Amazon Sumerian Timeline Component](entities-timeline.md)\.