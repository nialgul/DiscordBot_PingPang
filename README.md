import discord, Asuncion, os
from discord.ext import commands

game = discord.Game("따까리들을 감시")
bot = commands.Bot (command_prefix='!', status = discord.Status.onl ine, activity = game)
client = discord.client
bot . run(MTIxNjk2MjUxNTU1MzA5NTczMA.GRWv0m.KhZBoqJU4elsMqjLICt9yaG9mBwSbLPtinqNHU)

@bot.event
async def on_messenge(message):if message.author.bot:return None
if message.content.endswith("함"):
file = discord.File("C:/Users/admin/Desktop/👊🤖/함.jog")
await message.channel.send(file=file)
await message.channel.sand("그런 함은 침몰하였습니다
