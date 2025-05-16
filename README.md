# nai-node
# NAi Node

This is the official NAi Node client for contributing bandwidth and computing tasks to the NAi network. Users are rewarded in NAi tokens for sharing internet speed and completing tasks like CPU benchmark, SHA256 hashing, and ping tests.

---

## 🚀 How to Run

You can easily run a NAi node using Docker:

```bash
docker run -d \
  -e WALLET=your_wallet_address \
  -e SERVER_URL=http://14.224.196.125:6686 \
  --restart unless-stopped \
  --name nai-node-client \
  protocolv1/nai-node
