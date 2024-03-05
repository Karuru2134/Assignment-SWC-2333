public class Appointment
{
   private String patientName;
   private String apptDate;
   private String apptTime;
   private String dentistName;
   
   public Appointment ()
   {
       patientName = null;
       apptDate = null;
       apptTime = null;
       dentistName = null;
   }
   
   public Appointment (String patientName, String apptDate, String apptTime, String dentistName)
   {
       this.patientName = patientName;
       this.apptDate = apptDate;
       this.apptTime = apptTime; 
       this.dentistName = dentistName;
   }
   
   public void setPatientName (String patientName)
   {
       this.patientName = patientName;
   }
   
   public void setApptDate (String apptDate)
   {
       this.apptDate = apptDate;
   }
   
   public void setApptTime (String apptTime)
   {
       this.apptTime = apptTime;
   }
   
   public void setDentistName (String dentistName)
   {
       this.dentistName = dentistName;
   }
   
   public String getPatientName ()
   {
       return patientName;
   }
   
   public String getApptDate ()
   {
       return apptDate;
   }
   
   public String getApptTime ()
   {
       return apptTime;
   }
   
   public String getDentistName ()
   {
       return dentistName;
   }
   
   public String toString ()
   {
       return "Appointment Details" +
              "\nPatient Name : " + patientName +
              "\nDate : " + apptDate +
              "\nTime : " + apptTime +
              "\nDentist Name : " + dentistName;
   }
}
