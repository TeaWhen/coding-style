# TeaWhen Coding Style

## Commit Log

### Complete

Use full sentences (sentence case, including period). If the commit is issue related, add a prefix “[Verb #ID] ” (don’t forget the trailing space). Available verbs are **Fix**, **Close**, and **On** (**Fix** and **Close** will close the issue). Use simple past tense or simple present tense.

**For example:**
```
[Fix #3] Migrated to AFNetworking 2.0.
```

**But not:**
```
migrate to AFNetworking 2.0
```

### Explicit

Use explicit description.

**For example:**
```
Fixed table view cell text overflow.
```

**But not:**
```
bug fix
```

## Objective-C Style

Follow [NYTimes Style Guide](https://github.com/NYTimes/objective-c-style-guide).

Except that we write method implementation’s beginning bracket in a single line, as:

```
- (IBAction)dateChanged:(UIDatePicker *)sender
{
    self.dateField.text = [sender.date dateString];
}
```

One thing to emphasize, DO NOT use any abbreviations unless they are very common. Long variable names are not bad.
