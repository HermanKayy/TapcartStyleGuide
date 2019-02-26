
**IBOutlets Naming**

```
hello
```

*Preferred*
```swift
@IBOutlet weak var firstNameLabel
@IBOutlet weak var notesTextView: UITextView!
@IBOutlet weak var passwordTextField: UITextField!
@IBOutlet weak var emptyStateView: UIView!
```

*Not Preferred*
```swift
@IBOutlet weak var firstName: UILabel!
@IBOutlet weak var notesField: UITextView!
@IBOutlet weak var passwordTextField: UITextField!
@IBOutlet weak var emptyState: UIView!


