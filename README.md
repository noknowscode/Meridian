# Meridian Capital Terminal (Dark)

A desktop stock market dashboard: portfolio value and holdings, sector allocation, per-stock chart drill-down, a watchlist and a mock trade drawer. Charts are drawn with SkiaSharp and all data is mock.

## What's inside

- **Screens:** Dashboard, Stock Detail.
- **Custom controls:** `BrailleRevealControl`, `RevenueBarChartControl`, `SectorRingControl`, `SparklineControl`, `VolumeChartControl`, `VolumeSubChartControl`.

## Built with

- Uno Platform single project, `Uno.Sdk` 6.5.31 (pinned in `global.json`).
- Targets: WebAssembly, Desktop (net10.0).
- Material theme, Hosting and dependency injection, Uno Toolkit, MVUX, SkiaSharp, Skia renderer.

## Run it

You need the .NET 10 SDK. Run `uno-check` first on a fresh machine.

```bash
dotnet run --project Meridian/Meridian.csproj -f net10.0-desktop
```

## License

MIT. See [LICENSE](LICENSE).
