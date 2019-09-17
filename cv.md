#Anastasia Molodtsova
##**Contact info:**
* phone: +79179605345
* e-mail: molodtsovaav@gmail.com

##**Summary**
Hello! My name is Anastasia and I really want to become a front-end developer. I am 28 years old. I am an economist by education. 
 I graduated from school and university with an excellent certificate. I really love math. Now I realized that I want to learn programming. I took the http://rubyschool.us/ programming course, I studied SQL, QA/development theory. Now I work as a QA and study JS in parallel. 
 > I am happy to study in The Rolling Scopes School! 
 
##**Skills**
 Ruby, RoR, SQL, HTML, CSS, SQLite, ActiveRecord, Sinatra, Bootstrap, DevTools, PostMan, Fiddler, GIT, JIRA
                                                                                                       
##**Code examples**

     <%= form_for(resource, as: resource_name, url: registration_path(resource_name)) do |f| %>
        <%= render "devise/shared/error_messages", resource: resource %>
      
        <div class="field">
          <%= f.label :email %><br />
          <%= f.email_field :email, autofocus: true, autocomplete: "email" %>
        </div>
      
        <div class="field">
          <%= f.label :user_name %><br />
          <%= f.text_field :user_name %>
        </div>
      
        <div class="field">
          <%= f.label :password %>
          <% if @minimum_password_length %>
          <em>(<%= @minimum_password_length %> characters minimum)</em>
          <% end %><br />
          <%= f.password_field :password, autocomplete: "new-password" %>
        </div>
      
        <div class="field">
          <%= f.label :password_confirmation %><br />
          <%= f.password_field :password_confirmation, autocomplete: "new-password" %>
        </div>
      
        <div class="actions">
          <%= f.submit "Sign up" %>
        </div>
      <% end %>
      
      <%= render "devise/shared/links" %></addr>
      