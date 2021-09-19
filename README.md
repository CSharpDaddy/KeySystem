# KeySystem

Documentation:

Add "KeySystem.dll" to your project

add "using KeySystem;" to the top of your project with the other "using"


login code:

if (KeySystem.KeySystem.Checkkey(textBox1.Text, "https://pastebin.com/raw/NtiHpBUb")) //change that url to your own
            {
                Form2 form = new Form2();
                form.Show();
                this.Hide();
            }
-------------------------------------------------------------------------------------------

get key code:

KeySystem.KeySystem.GetKey("https://pastebin.com/raw/NtiHpBUb"); //change that url to your own

I kinda want credit for this API but imma give you an option to disable if you choose to disable it fuck you but anyways heres 
how to disable it 

bool Credits = false;
---------------------------------------------------------------------------------------------

What is KeySystem? its a C# whitelist system made simple i did all the coding for your so all you gotta do is add the urls if you wanna make money change the get key url to a linkvertise url or some other url shortner that pays out. Enjoy
