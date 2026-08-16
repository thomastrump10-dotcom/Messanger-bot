module.exports.config = {
  name: "war",
  version: "1.0.0",
  hasPermssion: 2,
  credits: "... - Long LTD",
  description: "War nát cái boxchat",
  commandCategory: "group",
  usages: "war with mention",
  cooldowns: 10,
  dependencies: {
    "fs-extra": "",
    "axios": ""
  }
};

module.exports.run = async function ({ api, args, Users, event }) {

  var mention = Object.keys(event.mentions)[0];

  if (!mention) {
    return api.sendMessage(
      "Please mention someone first.",
      event.threadID
    );
  }

  var name = event.mentions[mention];

  var a = function (text) {
    api.sendMessage({
      body: `@${name}, ${text}`,
      mentions: [
        {
          tag: `@${name}`,
          id: mention
        }
      ]
    }, event.threadID);
  };

  a("you have been warned. Don't start unnecessary drama.");

  setTimeout(() => {
    a("stop acting like a troublemaker.");
  }, 3000);

  setTimeout(() => {
    a("listen carefully and stop messing around 😋😋");
  }, 5000);

  setTimeout(() => {
    a("don't make this group chat more chaotic than it already is.");
  }, 7000);

  setTimeout(() => {
    a("seriously, calm down and stop the nonsense 🤬🤬");
  }, 9000);

  setTimeout(() => {
    a("enough drama. Say what you actually want to say.");
  }, 12000);

  setTimeout(() => {
    a("keep talking like that and everyone will know who the real troublemaker is.");
  }, 15000);

  setTimeout(() => {
    a("you have a lot of courage to keep arguing. 😒");
  }, 17000);

  setTimeout(() => {
    a("I don't even know how you still have the energy to keep arguing.");
  }, 20000);

  setTimeout(() => {
    a("your attitude needs an update.");
  }, 23000);

  setTimeout(() => {
    a("if you want to argue online, at least make a proper point.");
  }, 25000);

  setTimeout(() => {
    a("you really don't know when to stop.");
  }, 28500);

  setTimeout(() => {
    a("enough already. Stop creating unnecessary drama.");
  }, 31000);

  setTimeout(() => {
    a("one joke after another and still no useful point 😂");
  }, 36000);

  setTimeout(() => {
    a("you're making a lot of noise for someone with nothing useful to say.");
  }, 39000);

  setTimeout(() => {
    a("stop acting tough and just calm down 🙁😒");
  }, 40000);

  setTimeout(() => {
    a("one, two, three... your argument still makes no sense 🤬");
  }, 65000);

  setTimeout(() => {
    a("remember this: don't cross the line.");
  }, 70000);

  setTimeout(() => {
    a("today you're getting a full lecture about your attitude.");
  }, 75000);

  setTimeout(() => {
    a("now calm down and stop the drama 😒😒");
  }, 80000);

};
