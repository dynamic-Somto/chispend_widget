A flutter package the provides a widget for [ChiSpend](https://chispend.com/) marketplace.

## Requirement

- Android Support:	SDK 19+ or 20+
- IOS Support:	9.0+

## Feature

- Access to ChiSpend marketplace using [webview](https://pub.dev/packages/webview_flutter).
- Full ability to customise widget theme and colour.


## Usage
```dart
class ChiSpendExample extends StatelessWidget {
  const ChiSpendExample({Key? key}) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return ChiSpendWidget(
      primaryColor: Colors.green,
      chiSpendTheme: ChiSpendTheme.royal,
      maxAmountInUSD: 1000,
      onMessageReceived: (v) {
        print(v);
      },
    );
  }
}
```

## Additional information

Please refer to [webview package](https://pub.dev/packages/webview_flutter) if any issue is encountered.
