# PROJECT

This is a Chat Application developed with PHP, MySQL and JavaScript Ajax. Once you signed up successfully, you can start chatting with other members subscribed to the app.

![Alt text](screenshot/signup.png?raw=true "index.php page")
![Alt text](screenshot/main.png?raw=true "users.php page")
![Alt text](screenshot/chat.png?raw=true "chat.php page")
![Alt text](screenshot/login.png?raw=true "login.php page")

**Edit connect.php file with your credentials**

## SETUP

Download the code and put the folder inside htdocs folder of your XAMPP/MAMP. Create a new database named 'chatapp' and import the SQL file in the ChatApp folder (chatapp2.sql). Edit the config.php file in the PHP folder with your database credentials. Now, your chat application is ready to chat.

## DB (MySQL) Structure

Database chatapp -> table 'users'

user_id | int(11) | NOT NULL |

unique_id | int(255) | NOT NULL |

fname | varchar(255) | NOT NULL |

lname | varchar(255) | NOT NULL |

email | varchar(255) | NOT NULL |

password | varchar(255) | NOT NULL |

img | varchar(255) | NOT NULL |

status | varchar(255) | NOT NULL |


table 'messages'

msg_id | int(11) | NOT NULL |

incoming_msg_id | int(255) | NOT NULL |

outgoing_msg_id | int(255) | NOT NULL |

msg | varchar(1000) | NOT NULL |
