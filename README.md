# Attachment Library

## Example Usage

```seru
from "github.com/Serulian/attachment:master" import Attachment

var<Attachment<string>> myAttachment = Attachment<string>.Unique('myAttachment')

function<void> SomeFunction(someObject any) {
	// Get the value of the attachment on the object.
	var<string?> currentValue = myAttachment[someObject]

	// Set the value of the attachment on the object.
	myAttachment[someObject] = 'hello world'
}

```