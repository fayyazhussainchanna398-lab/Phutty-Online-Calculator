<!-- Cotton Price Wide Widget Section -->
<div style="max-width:900px; margin:40px auto; padding:20px; background:#fff; border-radius:12px; box-shadow:0 4px 18px rgba(0,0,0,0.1);">
  <h2 style="text-align:center; margin-bottom:12px; color:#232526;">US Cotton #2 Live Chart</h2>
  <div class="tradingview-widget-container">
    <div id="tradingview_cotton"></div>
    <script type="text/javascript" src="https://s3.tradingview.com/tv.js"></script>
    <script type="text/javascript">
      new TradingView.widget({
        "width": "100%",
        "height": 300,
        "symbol": "ICEUS:CT1!",
        "interval": "D",
        "timezone": "Etc/UTC",
        "theme": "light",
        "style": "1",
        "locale": "en",
        "toolbar_bg": "#f1f3f6",
        "enable_publishing": false,
        "withdateranges": true,
        "hide_side_toolbar": false,
        "save_image": false,
        "container_id": "tradingview_cotton"
      });
    </script>
  </div>
</div>
