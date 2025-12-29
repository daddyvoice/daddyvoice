## pt-br/eng
$ git clone https://github.com/journey-ad/Moe-Counter.git
$ cd Moe-Counter
$ pnpm install

$ pnpm start
# https://count.getloli.com/@daddyvoice?name=daddyvoice&theme=rule34&padding=7&offset=0&align=top&scale=1&pixelated=1&darkmode=auto
# APP_SITE=https://count.getloli.com

# Application port
APP_PORT=3000

# Database type: either 'sqlite' or 'mongodb'
DB_TYPE=sqlite

# If using MongoDB, provide the connection string
# DB_URL=mongodb://127.0.0.1:27017

# Database write interval in seconds (0 for real-time)
DB_INTERVAL=60

# Log level: either 'debug' | 'info' | 'warn' | 'error' | 'none'
LOG_LEVEL=debug

# Google Analytics `G-Tag` ID
# GA_ID=G-XXXX
