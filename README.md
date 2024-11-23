# Feedbacky CDN
- Getting free CDN for open source projects.

### Usage Via CDN <a name="cdn"></a>

- Feedbacky can be integrated also via CDN with `script` tags.

- Go to main `HTML` file. `(index.html)`

##### feedbacky-container

- Add a `div` element with the ID of `feedbacky-container`.

```html
<div id="feedbacky-container"></div>
```

##### CDN

- Add `CDN` using `script` tag. Then, customize Feedbacky component with `feedbacky.run()`.

```js
<script src="https://cdn.jsdelivr.net/npm/feedbacky-cdn@1.0.0/index.js"></script>

<script>
    feedbacky.run({
        googleSheetId: "95a57d16-dcc3-4f57-8e24-dfbba8e9e786",
        modalSuccessTitle: "Thanks for sharing your feedback!",
        sendButtonText: "Send Feedback",
        nameInputPlaceholder: "Your Name",
        surnameInputPlaceholder: "Your Surname",
        feedbackInputPlaceholder: "Your Feedback",
        modalSuccessIconSize: 100,
        modalSuccessIconColor: "green",
        feedbackyButtonIconSize: 45,
        modalTitle: "Share what you think with us...",
    });
</script>
```

### Props Table <a name="props"></a>

| Prop Name                  | Prop Type | Value (E.G.)                           | Requirement |
| :------------------------- | :-------- | :------------------------------------- | :---------- |
| `googleSheetId`            | `string`  | "95a57d16-dcc3-4f57-8e24-dfbba8e9e786" | `required`  |
| `modalSuccessTitle`        | `string`  | "Thanks for sharing your feedback!"    | `optional`  |
| `sendButtonText`           | `string`  | "Send Feedback"                        | `optional`  |
| `nameInputPlaceholder`     | `string`  | "Your Name..."                         | `optional`  |
| `surnameInputPlaceholder`  | `string`  | "Your Surname..."                      | `optional`  |
| `feedbackInputPlaceholder` | `string`  | "Your Feedback..."                     | `optional`  |
| `modalSuccessIconSize`     | `number`  | 100                                    | `optional`  |
| `modalSuccessIconColor`    | `string`  | green                                  | `optional`  |
| `feedbackyButtonIconSize`  | `number`  | 45                                     | `optional`  |
| `modalTitle`               | `string`  | "Share what you think with us..."      | `optional`  |

##### Details:
https://github.com/berkesayin/feedbacky-app
