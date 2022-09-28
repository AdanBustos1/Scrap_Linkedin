Simple Scrapping from Linkedin. +1700 jobs

DF: Jobs - Skills per job - Upgrade Jobs - Skills to upgrade




----Nota----

Si tienes guardado un registro de trabajos en una variable puedes introducirlas dentro del enlace en driver.get('enlace'), ya que esta muestra scrapea los trabajos que contengan la letra "a", simplemente cambialo de esta forma para obtener todos:

 #Vaciar el input de busqueda
 driver.find_element(By.ID, 'explore').find_element(By.ID, 'jobs--ac').send_keys(Keys.CONTROL + variable_con_trabajos, Keys.BACKSPACE)
