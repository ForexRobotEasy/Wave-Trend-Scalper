# Wave Trend Scalper

Wave Trend Scalper is a unique forex software developed by the Forex Robot Easy Team. Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit [https://forexroboteasy.com/forex-robot-review/wave-trend-scalper-review-unique-forex-software-tested-in-extreme-conditions/](https://forexroboteasy.com/forex-robot-review/wave-trend-scalper-review-unique-forex-software-tested-in-extreme-conditions/).

## Expert Initialization Function

The `OnInit` function is called during the expert initialization process. You can add any necessary initialization code in this function.

```cpp
int OnInit()
{
    // Add necessary initialization code here

    return(INIT_SUCCEEDED);
}
```

## Expert Deinitialization Function

The `OnDeinit` function is called when the expert is being unloaded from the chart or during the terminal shutdown. You can add any necessary deinitialization code in this function.

```cpp
void OnDeinit(const int reason)
{
    // Add necessary deinitialization code here
}
```

## Expert Start Function

The `OnStart` function is the main entry point of the expert. It is called once when the expert is initialized and is responsible for executing the main program logic.

```cpp
void OnStart()
{
    // Add necessary main program code here
}
```

## Expert Execution Function

The `OnTick` function is called on each tick of the chart. You can add your trading logic in this function to execute trades based on market conditions.

```cpp
void OnTick()
{
    // Add necessary trading logic here
}
```

## Expert Calculation Function

The `OnCalculate` function is called when a new bar appears or when the chart is refreshed. You can add any necessary calculation code in this function.

```cpp
void OnCalculate(const int rates_total, const int prev_calculated, const int begin, const double &price[])
{
    // Add necessary calculation code here
}
```

Please note that the provided code is a template and does not include any specific trading logic. You will need to customize the code according to your trading strategy.

For more information and to download the official version of Wave Trend Scalper, please visit the MQL5 website.
