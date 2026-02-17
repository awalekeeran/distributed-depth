# API Rate Limiting (Production APIs - Stripe, Github, AWS, Google)
  Sliding window is the backbone of fair rate limiting.

  ### How it works
  - Each user's request timestamps are stored(queue/log)
  - When a new request arrives, remove old timestamps beyond 'X' seconds
  - Allow only is count <= limit
 
  ### Why Sliding Window ??
  - More accurate than fixed windows
  - Avoids "bursting" at window boundaries
  - Used in :
    - Github API
    - Cloudflare
    - Stripe payments
    - AWS API Gateway
