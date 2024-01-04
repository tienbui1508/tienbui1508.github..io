---
title: Use SwiftLint to clean up your code
tags: [Software Development, Swift, SwiftLint]
style:
color:
description: Analyse your Swift code using SwiftLint - a free and open source.
---

Source: [Realm](https://github.com/realm/SwiftLint)

# Disable checking length violations

## For one line

To disable checking length violations in SwiftLint, use one the following comments:

```swift
// swiftlint:disable:next line_length

// swiftlint:disable:this line_length

// swiftlint:disable:previous line_length
```

## For a whole file

Add the disable comment to the beginning of the file:

```swift
// swiftlint:disable line_length
```

And add the enable comment to the end of the file:

```swift
// swiftlint:enable line_length
```

# Show SwiftLint result in Xcode

To get Xcode run SwiftLint automatically, select the project in Project Navigator, then select the target in Targets, then select the Build Phases tab. Add a Run Script Phase and copy the code below (for Apple silicon Macs):

```sh
if [[ "$(uname -m)" == arm64 ]]; then
    export PATH="/opt/homebrew/bin:$PATH"
fi

if which swiftlint > /dev/null; then
  swiftlint
else
  echo "warning: SwiftLint not installed, download from https://github.com/realm/SwiftLint"
fi
```

# Fix the errors automatically

In the console, run:

```sh
swiftlint --fix
```
