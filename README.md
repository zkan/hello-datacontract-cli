# Hello, datacontract-cli

Run schema and quality tests:

```bash
uv run datacontract test https://datacontract.com/examples/orders-latest/datacontract.yaml
```

Check diff:

```bash
uv run datacontract diff https://datacontract.com/examples/orders-latest/datacontract.yaml datacontract.yaml
```