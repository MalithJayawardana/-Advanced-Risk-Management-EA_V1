Here is the complete, professional English version of the README. It is fully formatted and ready to be pasted directly into your README.md file on GitHub!

🚀 AI_RiskManager EA (Advanced Risk Management Tool for MT5)
AI_RiskManager is a professional MetaTrader 5 (MT5) Expert Advisor (EA) designed specifically for strict risk execution. It is highly optimized for traders managing Funded Accounts (Prop Firms) who need precise risk control.

This EA automatically calculates the exact lot size based on your account balance, sets accurate Stop Loss and Take Profit levels based on your preferred Risk-to-Reward ratio, and executes trades with one click in milliseconds.

✨ Key Features
Auto Lot Size Calculation: Dynamically calculates the exact lot size based on your specified Risk Percentage (e.g., 0.25%) and Stop Loss in pips, automatically factoring in the specific Forex pair's tick value and point size.

On-Chart GUI Panel: Modify Risk %, SL pips, and RR Ratio directly from the on-chart dashboard without needing to open the standard EA input settings (F4/F7).

Dynamic Reward-to-Risk (RR): Automatically calculates the Take Profit level based on your specified RR ratio (e.g., inputting 3.0 sets a 1:3 RR) and the Stop Loss distance.

One-Click Execution: Instantly execute market orders using the custom graphical BUY and SELL buttons directly on the chart.

Advanced Error Checking: If a trade fails to execute (e.g., insufficient margin, requotes), the EA captures the exact error code and prints a detailed description in the "Experts" journal.

🛠️ Installation Guide
Open MetaTrader 5 and press F4 on your keyboard to launch MetaEditor.

In the left "Navigator" panel, right-click the Experts folder and select "New File".

Choose Expert Advisor (template), name the file AI_RiskManager, and click Finish.

Delete all the default code in the newly created file and paste the complete MQL5 source code into it.

Click the Compile button at the top toolbar. (Ensure the bottom log shows 0 errors, 0 warnings).

💻 How to Use
Ensure "Algo Trading" is enabled by clicking the button in the top MT5 toolbar (the icon should turn green).

Drag and drop the AI_RiskManager EA from the Navigator panel onto your desired trading chart.

In the pop-up settings window, navigate to the "Common" tab and check the box that says "Allow Algo Trading".

The custom GUI control panel will now appear on the top-left of your chart.

⚠️ Crucial Rule for the Chart UI:
Whenever you change a value (Risk %, SL, or RR) directly in the on-chart input boxes, you MUST press the 'ENTER' key on your keyboard after typing the new number. If you do not press Enter, MT5 will not register the updated text, and the EA will execute using the old value.

🔍 Troubleshooting
If trades are not executing when you click the BUY/SELL buttons:

Double-check that the main "Algo Trading" button in MT5 is green.

Open the "Toolbox" panel at the bottom of the MT5 terminal (Ctrl+T) and go to the "Experts" tab.

Check the log. The EA will print the exact reason the trade was rejected (e.g., AutoTrading disabled by client, Not enough money, or Invalid stops).

Developed utilizing AI quantitative trading logic. Optimized for MetaTrader 5.
