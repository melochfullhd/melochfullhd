client.on("messageCreate", async (message) => {
    await message.react("✔️"); // >
    await message.react("❌"); // >
const client = new Client({ intents: [Intents.FLAGS.GUILDS, Intents.FLAGS.GUILD_MESSAGES] });
