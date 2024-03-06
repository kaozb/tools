FROM lss233/chatgpt-mirai-qq-bot:browser-version
RUN pip install Werkzeug==2.3.0
ADD ./wecom_bot.py /app/platforms/wecom_bot.py
CMD ["/bin/bash","/app/docker/start.sh"]
