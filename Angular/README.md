
# Angular documentation

![](https://ovenfo.com/assets/img/logo/logo_up.png)

![](https://img.shields.io/github/stars/pandao/editor.md.svg) ![](https://img.shields.io/github/forks/pandao/editor.md.svg) ![](https://img.shields.io/github/tag/pandao/editor.md.svg) ![](https://img.shields.io/github/release/pandao/editor.md.svg) ![](https://img.shields.io/github/issues/pandao/editor.md.svg) ![](https://img.shields.io/bower/v/editor.md.svg)



####Component Creation

Each component must be created with project prefix in beginning part, then each component must be written as the next example

Bad implementation

```javascript
@Component({
    selector: 'reportcredit-template',
    styleUrls: ['./dmg.report-Credit-Template.css'],
    templateUrl: './report-CreditTemplate.html'
})
```

Good implementation

```javascript
@Component({
    selector: 'dmg-report-credit-template',
    styleUrls: ['./dmg.reportCreditTemplate.css'],
    templateUrl: './dmg.reportCreditTemplate.html'
})
```