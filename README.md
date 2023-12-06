# tgju-API
An API to get Prices from tgju.org

## How to use (for exmaple with curl)

Available Methods: GET

Available Types: RAW , JSON

Base URL(Protected By [Cloudflare](https://cloudflare.com/)): [api.mmdfazeli.tech](https://api.mmdfazeli.tech/)

---
### Get Prices as RAW (For Exmaple USD Price)
Request:
```fix
curl https://api.mmdfazeli.tech/arz/usd?type=RAW
```
Response:
```text
50414
```
---
### Get Prices as JSON (For Exmaple USD Price)
Request:
```fix
curl https://api.mmdfazeli.tech/arz/usd?type=JSON
```
Response:
```json
{
  "error": false,
  "message": null,
  "source": "tgju.org",
  "result": "50414"
}
```
---
#### Available Currencies
Euro: eur , euro

USD: dollar , usd

CAD: cad

---
## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Mohammadgb0078/tgju-API&type=Date)](https://star-history.com/#Mohammadgb0078/tgju-API&Date)
