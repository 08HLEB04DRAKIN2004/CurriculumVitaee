# HLEB DRAKIN, 19 y.o.
![image](/ava.jpg "ava")
****
# Contact information:
Phone: +375(25)-xxx-15-19
* [E-mail](адрес "https://mail.ru/g_drakin@mail.ru") 
* [Vkontakte](адрес "https://vk.com/gdrakin")
* [Telegram](адрес "https://t.me/drknhb")

# Briefly About Myself:
-----
I am a student of the Belarusian-Russian University. I study at the Faculty of Engineering and Economics. I am a software engineer.I like programming in :
- C#
- T-SQL
- HTML, CSS, JS
 ***
# Code Example
-----


```
namespace DeveloperApiCSharpSample
{
    class Program
    {
        static void Main(string[] args)
        {
            var config = new ClientConfiguration()
            {
                ApplicationId = "...",
                InAppProductId = "...",
                FlightId = "...",
                ClientId = "...",
                ClientSecret = "...",
                ServiceUrl = "https://manage.devcenter.microsoft.com",
                TokenEndpoint = "https://login.microsoftonline.com/<tenantid>/oauth2/token",
                Scope = "https://manage.devcenter.microsoft.com",
            };

            new FlightSubmissionUpdateSample(config).RunFlightSubmissionUpdateSample();
            new InAppProductSubmissionUpdateSample(config).RunInAppProductSubmissionUpdateSample();
            new InAppProductSubmissionCreateSample(config).RunInAppProductSubmissionCreateSample();
            new AppSubmissionUpdateSample(config).RunAppSubmissionUpdateSample();
        }
    }
}

```
