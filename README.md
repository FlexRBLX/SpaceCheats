# WeAreDevs API

# THIS NOT LONGER WORKS! WEAREDEVS/FLUXUS IS DISCOUNTINUED, NEW VERSION AT https://discord.gg/getindigo

⚠️ This project are for educational purposes only, if you do use this on Roblox and you get banned, that is your fault as you are breaking their Terms of Service.
Download API here
This is a Roblox exploiting I brought back WeAreDevs API that supports the UWP version of Roblox! There is no key system and it auto-updates to the latest version!

tldr: wearedevs api but it bypasses byfron

Getting started
To use this you need to use the UWP (Universal Windows Platform) version of the Roblox app which doesn't have Byfron. To do this, get Roblox from the Microsoft store!

How to create your own exploit
⚠️ Educational purposes only, video tutorial soon!
Create a new Visual Studios project. I recommend choosing the Windows Form App (.NET Framework)
image

Add the exploit API as a reference

Start using the API! Example:
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;
using WRD;

namespace Tutorial
{
    public partial class Form1 : Form
    {
        WRD.ExploitAPI WRD = new WRD.ExploitAPI();
        public Form1()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {
            WRD.SendLuaScript(richTextBox1.Text); // Runs script
        }

        private void button2_Click(object sender, EventArgs e)
        {
            WRD.LaunchExploit(); // Injects into Roblox
        }
    }
}

Your skidsploit will now work and auto-updates to the lastest version!

Attribution
The code for the actual injecting wasn't done by me.

The actual important DLLs are taken from WeAreDev's CDN, however for some reason they haven't updated WeAreDevs API to do this so I just did it myself.

You can complain this project is skidded but thats the point, its just a UWP port for the WeAreDevs API.
