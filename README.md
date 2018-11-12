# talkiepi fork

Push to talk API on raspberry pi



Enable talking client:
```
curl -4s http://127.0.0.1:8998/mic/on
```

Disable talking client:
```
curl -4s http://127.0.0.1:8998/mic/off
```


talkiepi is a headless capable Mumble client written in Go, written for walkie talkie style use on the Pi using GPIO pins for push to talk and LED status.  It is a fork of [barnard](https://github.com/layeh/barnard), which was a great jump off point for me to learn golang and have something that worked relatively quickly.

## License

MPL 2.0

## Author

- talkiepi - [Daniel Chote](https://github.com/dchote)
- Barnard,Gumble Author - Tim Cooper (<tim.cooper@layeh.com>)

