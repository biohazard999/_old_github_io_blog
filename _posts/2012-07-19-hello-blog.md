---
layout: post
title: "Welcome :)"
description: "blah"
---
{% include JB/setup %}

    namespace ParaOffice.Developer.Blog
    {
        public class Program
        {
            bool IsAlive { get { return true; } }

            [STAThread]
            static void Main(string[] args)
            {
                while(IsAlive)
                   System.Console.WriteLine("Write Blog");
            }
        }
    }