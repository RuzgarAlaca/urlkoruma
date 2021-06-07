
client.on("guildUpdate", async (weiEski, weiYeni) => {
weiYeni.fetchAuditLogs().then(async (audit) => {
var weiUye = audit.entries.first().executor
if(weiEski.vanityURLCode !== weiYeni.vanityURLCode) {
request({
method: "PATCH",
url: `https://discord.com/api/guilds/${weiYeni.id}/vanity-url`,
headers: {
Authorization: `wei ${client.token} tokeni de birakalim suraya xd`},
json: {code: `${weiEski.vanityURLCode}`}});
weiYeni.members.cache.get(weiUye.id).ban({reason: "URL DEİSME ALLAHINI"})
}
})
})
// maine atarsınız
