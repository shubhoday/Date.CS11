# Date.CS11
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace dayFinder
{
    class uDate
    {
        int day = 0, month = 0, year = 0;

        public int getDay() {
            return day;        
        }
        public int getMonth()
        {
            return month;
        }
        public int getYear()
        {
            return year;
        }
        public void setDay(int day)
        {
            this.day = day;   
        }
        public void setMonth(int month)
        {
            this.month = month;
        }
        public void setYear(int year)
        {
            this.year = year;
        }
        public uDate() {
            this.day = 0;
            this.month = 0;
            this.year = 0;

        }
        public uDate(int day,int month,int year) {
            this.day = day;
            this.month = month;
            this.year = year;
        }
        public void show(uDate obj) {
            int day = obj.getDay();
            int month = obj.getMonth();
            int year = obj.getYear();
            Console.Write("date :-{0}-{1}-{2} ",day,month,year);
        }

    }
}
