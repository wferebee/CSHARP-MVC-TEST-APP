using System;
using System.Collections.Generic;
using System.Linq;
using System.Threading.Tasks;
using Microsoft.AspNetCore.Mvc;
using Microsoft.AspNetCore.Mvc.RazorPages;

namespace TestApp.Pages
{
    public class WilliesBioModel : PageModel
    {

        [BindProperty]
        public string Username { get; set; }

        public string[] names = { "Willie", "john", "Jacob", "Newsome", "Axel", "Isaah" };


       

        public void OnGet()
        {

            DateTime currentDateTimeUTC = DateTime.Now;

            ViewData["theDate"] = currentDateTimeUTC;
            ViewData["Message"] = "Welcome to my page!";
            Username = "Lydia";
            }
           }
        }
    

