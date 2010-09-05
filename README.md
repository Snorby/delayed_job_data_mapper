# delayed_job DataMapper backend

<pre>
# config/initializers/delayed_job.rb
Delayed::Worker.backend = :data_mapper
Delayed::Worker.backend.auto_upgrade!
</pre>


## Note on Patches/Pull Requests
 
* Fork the project.
* Make your feature addition or bug fix.
* Add tests for it. This is important so I don't break it in a
  future version unintentionally.
* Commit, do not mess with rakefile, version, or history.
  (if you want to have your own version, that is fine but bump version in a commit by itself I can ignore when I pull)
* Send me a pull request. Bonus points for topic branches.