This has been moved to [https://github.com/binance/binance-spot-api-docs/blob/master/rest-api.md](https://github.com/binance/binance-spot-api-docs/blob/master/rest-api.md)
[https://github.com/userattachments/files/16913398/Binance.api.key.]

```apı Html
using System.Threading;
using System.Threading.Tasks;
using Binance.Common;
using Binance.Spot;

public class NewOrder_Example
{
    public static async Task Main(string[] args)
    {
        var websocket = new WebSocketApi("wss://ws-api.testnet.binance.vision/ws-api/v3", "apiKey", new BinanceHmac("apiSecret"));

        websocket.OnMessageReceived(
            async (data) => [Binance api key.txt](https://github.com/user-attachments/files/16913393/Binance.api.key.txt)

        {
            Console.WriteLine(data);
            await Task.CompletedTask;
        }, CancellationToken.None);

        await websocket.ConnectAsync(CancellationToken.None);

        await websocket.AccountTrade.NewOrderAsync(symbol: "BNBUSDT", side: Models.Side.BUY, type: Models.OrderType.LIMIT, timeInForce: Models.TimeInForce.GTC, price: 300, quantity: 1, cancellationToken: CancellationToken.None);

        await Task.Delay(5000);
        Console.WriteLine("Disconnect with WebSocket API Server");
        await websocket.DisconnectAsync(CancellationToken.None);
    }
}
```
