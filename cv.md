# Dmitry Osipenko

### Contact:

- Email: dmtr.osipenko@gmail.com
- Telegram: @dosenk
- linkedin: [Dmitry Osipenko](https://www.linkedin.com/in/dmtros/)

### SKILLS:

- PHP
- Linux (Ubuntu/Debian, Centos/RedHat)
- Mysql
- Apache
- Nginx
- Docker
- KVM (Proxmox)
  <<<<<<< HEAD

```PHP
class data
{
    public $path;
    public $fileType;
    public $fileName;
    private $_fileError;
    private $_fileTmpName;

    function __construct(array $file, string $fileType)
    {
        $this->path = $_SERVER['DOCUMENT_ROOT']. '/logger/files/'.$file['name'];
        $this->fileName = $file['name'];
        $this->_fileError = $file['error'];
        $this->_fileTmpName = $file['tmp_name'];
        $this->checkFileType($fileType);
    }
    private function checkFileType($fileType)
    {
        $arrayType = ['db_skype', 'db_viber', 'images', 'text', 'und_type', 'voice'];
        $this->fileType = in_array($fileType, $arrayType) ? $fileType : 'und_type';
    }

    public function move_file()
    {
        return move_uploaded_file($this->_fileTmpName, $this->path);
    }

}
```

### Education

- BSUIR (2011) - telecommunications engineer
- # IT-Academy (2018) - ICND Interconnecting Cisco Networking Devices Part 1

### Experience

###### Network manager

- configuring and maintaining servers (KVM (Proxmox), VMware)
- maintenance of network equipment: Cisco, D-link, Mikrotik
- working with MySql databases
- development in JS, PHP 5-7 (Laravel - entry-level)
- Docker, Linux (Ubuntu/Debian, Centos/RedHat), Apache, Nginx

### Education

- BSUIR (2011) - telecommunications engineer
- IT-Academy (2018) - ICND Interconnecting Cisco Networking Devices Part 1

> > > > > > > rsschool-cv-html

### English

Pre-Intermediate (A2)
