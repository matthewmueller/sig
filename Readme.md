# sig

Trap signals and cancel contexts. Simple, but I use this everywhere.

## Usage

```go
ctx := sig.Trap(syscall.SIGINT, syscall.SIGTERM)
```

## License

MIT
