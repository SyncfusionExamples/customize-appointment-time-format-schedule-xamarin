# How to customize the appointment time format in Xamarin.Forms Schedule (SfSchedule)

You can customize the appointment time format by using the [TimeFormat](https://help.syncfusion.com/cr/xamarin/Syncfusion.SfSchedule.XForms.AgendaViewStyle.html#Syncfusion_SfSchedule_XForms_AgendaViewStyle_TimeFormat) property of [AgendaViewStyle](https://help.syncfusion.com/cr/xamarin/Syncfusion.SfSchedule.XForms.AgendaViewStyle.html) in Xamarin.Forms [SfSchedule](https://www.syncfusion.com/xamarin-ui-controls/xamarin-scheduler).

**XAML**

You can set “HH: mm” to TimeFormat property of AgnedaViewStyle to show appointments with 24 hr time format.
```
<schedule:SfSchedule.MonthViewSettings>
    <schedule:MonthViewSettings ShowAgendaView="True">
        <schedule:MonthViewSettings.AgendaViewStyle>
            <schedule:AgendaViewStyle TimeFormat="HH:mm"/>
        </schedule:MonthViewSettings.AgendaViewStyle>
    </schedule:MonthViewSettings>
</schedule:SfSchedule.MonthViewSettings>
```

> **Note:**
> Agenda View Appearance customization is not applicable for UWP and WPF platforms.

KB article - [How to customize the appointment time format in Xamarin.Forms Schedule (SfSchedule)](https://www.syncfusion.com/kb/12261/how-to-customize-the-appointment-time-format-in-xamarin-forms-schedule-sfschedule)