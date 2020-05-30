# ByteCoin
A simple iOS app to convert BTC price to selected currency. It uses [coinapi.io](coinapi.io) API to fetch current rate of BTC in selected curreny.

If you want to run the project in your workspace
<ol>
<li>Clone the repo </li>
<li>Make a new file in project directory as "Constants.swift" </li>
<li>Copy the follwing code and give your API key to apiKey.</li>
</ol>

```
struct Constants {
    static let API_KEY = "YOUR_API_KEY"
}
```

