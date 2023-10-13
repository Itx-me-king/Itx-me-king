- 👋 Hi, I’m @Itx-me-king
- 👀 I’m interested in you
- 🌱 I’m currently Studying 
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Itx-me-king/Itx-me-king is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
from tg_bot.sample_config import Config


class Development(Config):
    OWNER_ID = 1499962818  # my telegram ID
    OWNER_USERNAME = "@Itx_Me_king"  # my telegram username
    API_KEY = "6115013211:AAHWJVL0Fe6_rK15yQ2DXhmTiScV9Qx_xi0"  # my api key, as provided by the botfather
    SQLALCHEMY_DATABASE_URI = 'postgresql://username:password@localhost:5432/database'  # sample db credentials
    MESSAGE_DUMP = '-134567230' # some group chat that your bot is a member of
    USE_MESSAGE_DUMP = True
    SUDO_USERS = [18673980, 83489514]  # List of id's for users which have sudo access to the bot.
    LOAD = [Error 404]
    NO_LOAD = ['translation']
