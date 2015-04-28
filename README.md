# ginerus
Basic Logging Middleware for Gin using Logrus

## Usage

Using logrus' standard logger.

```go
engine := gin.New()
engine.Use(ginerus.Ginerus())
```

Using a custom logrus Logger.

```go
engine := gin.New()
engine.Use(ginerus.GinerusWithLogger(someLogger))
```
